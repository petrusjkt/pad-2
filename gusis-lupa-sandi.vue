<template>
    <div :class="$style.lupaKataSandi">
      <div :class="$style.wrapper">
        <div :class="$style.body">
          <div :class="$style.illustration">
            <div :class="$style.frame">
              <img :class="$style.shapeIcon" alt="" src="/shape.svg" />
              <img :class="$style.shapeIcon1" alt="" src="/shape2@2x.png" />
            </div>
          </div>
          <div :class="$style.card">
            <div :class="$style.logo">
              <div :class="$style.warehouse1StreamlineCoresParent">
                <img
                  :class="$style.warehouse1StreamlineCoresIcon"
                  alt=""
                  src="/warehouse1streamlinecoresvg.svg"
                />
                <div :class="$style.sistemInformasiParent">
                  <b :class="$style.sistemInformasi">Sistem Informasi </b>
                  <b :class="$style.sistemInformasi"
                    >Peminjaman Alat dan Gudang</b
                  >
                </div>
              </div>
            </div>
            <div :class="$style.text">
              <div :class="$style.text1">
                <div :class="$style.marketingAutomation">
                  <span :class="$style.lupaKataSandi1">Lupa Kata Sandi</span>
                  <span :class="$style.span"> </span>
                  <span :class="$style.span1">🔒</span>
                </div>
                <div :class="$style.lookAgainAt">
                  Masukkan alamat email dan kami akan mengirimkan instruksi untuk
                  mereset kata sandi akun Anda
                </div>
              </div>
              <div :class="$style.textfieldoutlined">
                <div :class="$style.input">
                  <div :class="$style.inactive">
                    <div :class="$style.label">Email</div>
                    <div :class="$style.adornmentEnd">
                      <img
                        :class="$style.warehouse1StreamlineCoresIcon"
                        alt=""
                        src="/removeredeye.svg"
                      />
                    </div>
                  </div>
                </div>
              </div>
              <div :class="$style.button" @click="onButtonContainerClick">
                <div :class="$style.unstyledbutton">
                  <div :class="$style.button1">kirim email</div>
                </div>
              </div>
              <div :class="$style.link">
                <img
                  :class="$style.arrowbackiosIcon"
                  alt=""
                  src="/arrowbackios.svg"
                  @click="onArrowBackIosIconClick"
                />
                <div :class="$style.lookAgainAt1" @click="onLookAgainAtClick">
                  Kembali ke Masuk
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  <script lang="ts">
    import { defineComponent } from "vue";
  
    export default defineComponent({
      name: "LupaKataSandi",
      methods: {
        onButtonContainerClick() {
          this.$router.push("/reset-kata-sandi");
        },
        onArrowBackIosIconClick() {
          // Please sync "Login" to the project
        },
        onLookAgainAtClick() {
          // Please sync "Login" to the project
        },
      },
    });
  </script>
  <style module>
    .shapeIcon {
      position: absolute;
      top: 0px;
      left: 118px;
      width: 1322px;
      height: 291px;
    }
    .shapeIcon1 {
      position: absolute;
      top: 110px;
      left: 210px;
      width: 137.2px;
      height: 125px;
      object-fit: cover;
    }
    .frame {
      position: absolute;
      top: 0px;
      left: 0px;
      width: 1440px;
      height: 291px;
    }
    .illustration {
      position: absolute;
      top: 662px;
      left: 0px;
      width: 1440px;
      height: 291px;
    }
    .warehouse1StreamlineCoresIcon {
      width: 24px;
      position: relative;
      height: 24px;
      overflow: hidden;
      flex-shrink: 0;
    }
    .sistemInformasi {
      position: relative;
      line-height: 15px;
    }
    .sistemInformasiParent {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
    }
    .warehouse1StreamlineCoresParent {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      gap: var(--gap-5xs);
    }
    .logo {
      height: 60px;
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      justify-content: center;
    }
    .lupaKataSandi1 {
      font-weight: 600;
    }
    .span {
      font-weight: 500;
    }
    .span1 {
      font-family: var(--font-roboto);
    }
    .marketingAutomation {
      width: 392px;
      position: relative;
      letter-spacing: 0.18px;
      line-height: 32px;
      display: inline-block;
      height: 38px;
      flex-shrink: 0;
    }
    .lookAgainAt {
      width: 392px;
      position: relative;
      font-size: var(--light-components-button-medium-size);
      letter-spacing: 0.15px;
      line-height: 21px;
      color: var(--light-text-secondary);
      display: inline-block;
    }
    .text1 {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      padding: 0px 0px var(--padding-7xl);
      font-size: var(--light-typography-h5-size);
    }
    .label {
      flex: 1;
      position: relative;
      letter-spacing: 0.15px;
      line-height: 24px;
    }
    .adornmentEnd {
      display: none;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
    }
    .inactive {
      align-self: stretch;
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      justify-content: flex-start;
      padding: var(--padding-base) 0px var(--padding-base) var(--padding-8xs);
      gap: var(--gap-5xs);
    }
    .input {
      align-self: stretch;
      border-radius: var(--br-5xs);
      border: 1px solid var(--light-other-outlined-border);
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      padding: 0px var(--padding-xs);
    }
    .textfieldoutlined {
      align-self: stretch;
      border-radius: var(--br-5xs);
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      padding: 0px 0px var(--padding-base);
      color: var(--light-text-disabled);
    }
    .button1 {
      position: relative;
      letter-spacing: 0.46px;
      line-height: 26px;
      text-transform: uppercase;
      font-weight: 500;
    }
    .unstyledbutton {
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      padding: var(--padding-5xs) var(--padding-7xl);
    }
    .button {
      align-self: stretch;
      box-shadow: var(--light-elevation-3);
      border-radius: var(--br-5xs);
      background-color: var(--light-primary-main);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      font-size: var(--light-components-button-large-size);
      color: var(--light-secondary-contrast);
    }
    .arrowbackiosIcon {
      width: 20px;
      position: relative;
      height: 20px;
      overflow: hidden;
      flex-shrink: 0;
      cursor: pointer;
    }
    .lookAgainAt1 {
      position: relative;
      letter-spacing: 0.15px;
      line-height: 24px;
      cursor: pointer;
    }
    .link {
      align-self: stretch;
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center;
      padding: var(--padding-xl) 0px 0px;
      gap: var(--gap-7xs);
      text-align: center;
      color: var(--light-primary-main);
    }
    .text {
      align-self: stretch;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      font-size: var(--light-typography-body-1-size);
    }
    .card {
      position: absolute;
      top: 304px;
      left: 496px;
      box-shadow: var(--light-elevation-card);
      border-radius: var(--br-3xs);
      background-color: var(--light-secondary-contrast);
      width: 448px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      padding: var(--padding-39xl) var(--padding-9xl) var(--padding-17xl);
      box-sizing: border-box;
    }
    .body {
      align-self: stretch;
      flex: 1;
      position: relative;
    }
    .wrapper {
      align-self: stretch;
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
    }
    .lupaKataSandi {
      width: 100%;
      position: relative;
      background-color: var(--light-background-body-background1);
      height: 1024px;
      overflow: hidden;
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      justify-content: center;
      text-align: left;
      font-size: var(--font-size-2xs);
      color: var(--light-text-primary);
      font-family: var(--light-components-chip);
    }
  </style>
  