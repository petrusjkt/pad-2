<template>
  <div :class="$style.login">
    <div :class="$style.wrapper">
      <div :class="$style.body">
        <div :class="$style.illustration">
          <div :class="$style.mask" />
          <div :class="$style.bgIllustration">
            <img :class="$style.shapeIcon" alt="" src="@/assets/shape.svg" />
            <div :class="$style.frame">
              <img :class="$style.shapeIcon1" alt="" src="/shape1@2x.png" />
            </div>
          </div>
          <div :class="$style.illustration1">
            <div :class="$style.illustration2">
              <img :class="$style.icon" alt="" src="/0277-1@2x.png" />
            </div>
            <div :class="$style.card">
              <div :class="$style.title">
                <img :class="$style.hardwareIcon" alt="" src="/hardware.svg" />
              </div>
            </div>
            <div :class="$style.card1">
              <img
                :class="$style.squarefootIcon"
                alt=""
                src="/squarefoot.svg"
              />
            </div>
            <div :class="$style.card2">
              <img
                :class="$style.waterdamageIcon"
                alt=""
                src="/waterdamage.svg"
              />
            </div>
          </div>
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
        </div>
        <div :class="$style.form">
          <div :class="$style.text">
            <div :class="$style.text1">
              <div :class="$style.marketingAutomation">
                <span :class="$style.selamatDatang">Selamat datang!</span>
                <b> </b>
                <span :class="$style.span">👋🏻</span>
              </div>
              <div :class="$style.lookAgainAt">
                Silakan isi data di bawah untuk masuk ke akun Anda!
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
            <div :class="$style.textfieldoutlined1">
              <div :class="$style.input">
                <div :class="$style.labelContainer">
                  <div :class="$style.label1">Passwoard</div>
                </div>
                <div :class="$style.active">
                  <div :class="$style.label">Kata sandi</div>
                  <div :class="$style.adornmentEnd1">
                    <img
                      :class="$style.warehouse1StreamlineCoresIcon"
                      alt=""
                      src="/removeredeye.svg"
                    />
                  </div>
                </div>
              </div>
            </div>
            <div :class="$style.link">
              <div :class="$style.checkbox">
                <div :class="$style.padding">
                  <img
                    :class="$style.warehouse1StreamlineCoresIcon"
                    alt=""
                    src="/checkboxoutlineblank.svg"
                  />
                </div>
                <div :class="$style.label2">Ingat saya</div>
              </div>
              <div :class="$style.lookAgainAt1">Lupa kata sandi?</div>
            </div>
            <div :class="$style.button">
              <div :class="$style.unstyledbutton">
                <div :class="$style.button1">Masuk</div>
              </div>
            </div>
            <div :class="$style.link1">
              <div :class="$style.label">
                <span>Belum memiliki akun?</span>
                <span :class="$style.span1"> </span>
                <span :class="$style.daftar">Daftar</span>
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
    name: "Login",
  });
</script>
<style module>
  .mask {
    position: absolute;
    top: 0px;
    left: 0px;
    background-color: var(--light-background-body-background);
    width: 965.5px;
    height: 1026px;
  }
  .shapeIcon {
    position: absolute;
    top: 0px;
    left: 153.7px;
    width: 836.3px;
    height: 291px;
  }
  .shapeIcon1 {
    position: absolute;
    top: 128px;
    left: 254.9px;
    width: 147.5px;
    height: 135.1px;
    object-fit: cover;
  }
  .frame {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 989px;
    height: 291px;
    overflow: hidden;
  }
  .bgIllustration {
    position: absolute;
    top: 625px;
    left: 0px;
    width: 990px;
    height: 291px;
  }
  .icon {
    width: 207px;
    position: relative;
    height: 554px;
    object-fit: cover;
  }
  .illustration2 {
    position: absolute;
    top: 134px;
    left: 26.4px;
    width: 653px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
  }
  .hardwareIcon {
    width: 100px;
    position: relative;
    height: 100px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .title {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: var(--padding-xl);
  }
  .card {
    position: absolute;
    top: 95px;
    left: 0px;
    box-shadow: var(--light-elevation-card);
    border-radius: var(--br-81xl);
    background-color: var(--light-primary-contrast);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .squarefootIcon {
    width: 75px;
    position: relative;
    height: 75px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .card1 {
    position: absolute;
    top: 0px;
    left: 447.7px;
    box-shadow: var(--light-elevation-card);
    border-radius: var(--br-3xs);
    background-color: var(--light-primary-contrast);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: var(--padding-xl);
  }
  .waterdamageIcon {
    width: 50px;
    position: relative;
    height: 50px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .card2 {
    position: absolute;
    top: 395px;
    left: 497px;
    box-shadow: var(--light-elevation-card);
    border-radius: var(--br-81xl);
    background-color: var(--light-primary-contrast);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: var(--padding-xl);
  }
  .illustration1 {
    position: absolute;
    top: 144px;
    left: 144.3px;
    width: 679.4px;
    height: 688px;
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
    position: absolute;
    top: 31px;
    left: 35.2px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
  }
  .illustration {
    width: 990px;
    position: relative;
    height: 1026px;
  }
  .selamatDatang {
    font-weight: 600;
  }
  .span {
    font-family: var(--font-roboto);
  }
  .marketingAutomation {
    width: 394px;
    position: relative;
    letter-spacing: 0.18px;
    line-height: 32px;
    display: inline-block;
    height: 38px;
    flex-shrink: 0;
  }
  .lookAgainAt {
    width: 394px;
    position: relative;
    font-size: var(--light-typography-body-2-size);
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
    padding: 0px 0px var(--padding-5xl);
    font-size: var(--font-size-5xl);
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
  .label1 {
    position: relative;
    letter-spacing: 0.15px;
    line-height: 12px;
  }
  .labelContainer {
    background-color: var(--light-primary-contrast);
    height: 2px;
    display: none;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px var(--padding-9xs);
    box-sizing: border-box;
  }
  .adornmentEnd1 {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
  }
  .active {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: var(--padding-mini) 0px var(--padding-mini) var(--padding-8xs);
    gap: var(--gap-5xs);
    font-size: var(--light-components-input-text-size);
    color: var(--light-text-disabled);
  }
  .textfieldoutlined1 {
    align-self: stretch;
    border-radius: var(--br-5xs);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    font-size: var(--light-components-input-label-size);
    color: var(--light-text-secondary);
  }
  .padding {
    border-radius: var(--br-2xl);
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-4xs);
  }
  .label2 {
    position: relative;
    letter-spacing: 0.15px;
    line-height: 21px;
  }
  .checkbox {
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
  }
  .lookAgainAt1 {
    flex: 1;
    position: relative;
    letter-spacing: 0.15px;
    line-height: 21px;
    color: var(--light-primary-main);
    text-align: right;
  }
  .link {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: 0px 0px var(--padding-base);
    gap: var(--gap-5xs);
    font-size: var(--light-typography-body-2-size);
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
    font-size: var(--light-components-button-large-size);
    color: var(--light-primary-contrast);
  }
  .span1 {
    color: var(--light-text-primary);
    white-space: pre-wrap;
  }
  .daftar {
    color: var(--light-primary-main);
  }
  .link1 {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    padding: var(--padding-9xl) 0px 0px;
    text-align: center;
    color: var(--light-text-secondary);
  }
  .text {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .form {
    width: 450px;
    background-color: var(--light-primary-contrast);
    height: 1024px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: center;
    padding: 48px var(--padding-9xl) var(--padding-17xl);
    box-sizing: border-box;
    font-size: var(--light-components-input-text-size);
  }
  .body {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
  }
  .wrapper {
    align-self: stretch;
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .login {
    width: 100%;
    position: relative;
    background-color: var(--light-background-body-background);
    height: 1024px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: center;
    text-align: left;
    font-size: var(--font-size-2xs);
    color: var(--light-text-primary);
    font-family: var(--light-typography-body-2);
  }
</style>
