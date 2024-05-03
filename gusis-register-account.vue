<template>
    <div :class="$style.registerMultiStepsAccount">
      <div :class="$style.wrapper">
        <div :class="$style.body">
          <div :class="$style.form">
            <img :class="$style.icon" alt="" src="/0748-1@2x.png" />
          </div>
          <div :class="$style.wrapper1">
            <div :class="$style.stepper">
              <div :class="$style.step">
                <img
                  :class="$style.baseStepElements"
                  alt=""
                  src="/base-step-elements1.svg"
                />
                <div :class="$style.div">01</div>
                <div :class="$style.content">
                  <div :class="$style.accountDetails">Akun</div>
                  <div :class="$style.enterYourAccount">Detail Akun</div>
                </div>
              </div>
              <div :class="$style.connector" />
              <div :class="$style.step">
                <img
                  :class="$style.baseStepElements"
                  alt=""
                  src="/base-step-elements2.svg"
                />
                <div :class="$style.div">02</div>
                <div :class="$style.content">
                  <div :class="$style.accountDetails">Personal</div>
                  <div :class="$style.enterYourAccount">Informasi Pribadi</div>
                </div>
              </div>
              <div :class="$style.connector1" />
              <div :class="$style.step2">
                <img
                  :class="$style.baseStepElements"
                  alt=""
                  src="/base-step-elements2.svg"
                />
                <div :class="$style.div">03</div>
                <div :class="$style.content2">
                  <div :class="$style.accountDetails">Billing</div>
                  <div :class="$style.enterYourAccount">Payment Details</div>
                </div>
              </div>
            </div>
            <div :class="$style.text">
              <div :class="$style.text1">
                <div :class="$style.marketingAutomation">Informasi Akun</div>
                <div :class="$style.lookAgainAt">Masukkan detail akun Anda</div>
              </div>
              <div :class="$style.input">
                <div :class="$style.textfieldoutlined">
                  <div :class="$style.input1">
                    <div :class="$style.inactive">
                      <div :class="$style.label">Email</div>
                      <div :class="$style.adornmentEnd">
                        <img
                          :class="$style.removeredeyeIcon"
                          alt=""
                          src="/removeredeye.svg"
                        />
                      </div>
                    </div>
                  </div>
                </div>
                <div :class="$style.textfieldoutlined">
                  <div :class="$style.input1">
                    <div :class="$style.inactive">
                      <div :class="$style.label">Nomor telepon</div>
                      <div :class="$style.adornmentEnd">
                        <img
                          :class="$style.removeredeyeIcon"
                          alt=""
                          src="/removeredeye.svg"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div :class="$style.input">
                <div :class="$style.textfieldoutlined">
                  <div :class="$style.input1">
                    <div :class="$style.inactive">
                      <div :class="$style.label">Kata sandi</div>
                      <div :class="$style.adornmentEnd">
                        <img
                          :class="$style.removeredeyeIcon"
                          alt=""
                          src="/removeredeye.svg"
                        />
                      </div>
                    </div>
                  </div>
                </div>
                <div :class="$style.textfieldoutlined">
                  <div :class="$style.input1">
                    <div :class="$style.inactive">
                      <div :class="$style.label">Konfirmasi kata sandi</div>
                      <div :class="$style.adornmentEnd">
                        <img
                          :class="$style.removeredeyeIcon"
                          alt=""
                          src="/removeredeye.svg"
                        />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div :class="$style.action">
                <div :class="$style.button" @click="onButtonContainerClick">
                  <div :class="$style.unstyledbutton">
                    <div :class="$style.content3">
                      <img
                        :class="$style.maskedIcon"
                        alt=""
                        src="/masked-icon.svg"
                      />
                      <div :class="$style.button1">masuk</div>
                    </div>
                  </div>
                </div>
                <div :class="$style.button2" @click="onButtonContainer1Click">
                  <div :class="$style.unstyledbutton">
                    <div :class="$style.content3">
                      <div :class="$style.button1">selanjutnya</div>
                      <img
                        :class="$style.maskedIcon"
                        alt=""
                        src="/masked-icon1.svg"
                      />
                    </div>
                  </div>
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
      name: "RegisterMultiStepsAccount",
      methods: {
        onButtonContainerClick() {
          // Please sync "Login" to the project
        },
        onButtonContainer1Click() {
          this.$router.push("/");
        },
      },
    });
  </script>
  <style module>
    .icon {
      width: 200px;
      position: relative;
      height: 554.9px;
      object-fit: cover;
    }
    .form {
      width: 450px;
      background-color: var(--light-background-body-background1);
      height: 1024px;
      overflow: hidden;
      flex-shrink: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .baseStepElements {
      width: 20px;
      position: relative;
      border-radius: var(--br-45xl);
      height: 20px;
      overflow: hidden;
      flex-shrink: 0;
    }
    .div {
      position: relative;
      letter-spacing: 0.25px;
      line-height: 40px;
      font-weight: 500;
    }
    .accountDetails {
      position: relative;
      letter-spacing: 0.1px;
      line-height: 21px;
      font-weight: 500;
    }
    .enterYourAccount {
      position: relative;
      font-size: var(--light-components-input-label-size);
      letter-spacing: 0.4px;
      line-height: 14px;
      color: var(--light-text-secondary);
    }
    .content {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      font-size: var(--light-typography-body-2-size);
    }
    .step {
      overflow: hidden;
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      gap: var(--gap-5xs);
    }
    .connector {
      flex: 1;
      position: relative;
      border-radius: var(--br-21xl);
      background-color: var(--light-primary-main);
      height: 3px;
      opacity: 0.12;
    }
    .connector1 {
      width: 81.5px;
      position: relative;
      border-radius: var(--br-21xl);
      background-color: var(--light-primary-main);
      height: 3px;
      display: none;
      opacity: 0.12;
    }
    .content2 {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      font-size: var(--light-typography-body-2-size);
      color: var(--light-text-primary);
    }
    .step2 {
      overflow: hidden;
      display: none;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      gap: var(--gap-5xs);
      color: var(--light-text-disabled);
    }
    .stepper {
      width: 697px;
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      gap: var(--gap-5xs);
    }
    .marketingAutomation {
      width: 394px;
      position: relative;
      line-height: 133.4%;
      font-weight: 500;
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
      font-size: var(--light-typography-h5-size);
      color: var(--light-text-primary);
    }
    .label {
      flex: 1;
      position: relative;
      letter-spacing: 0.15px;
      line-height: 24px;
    }
    .removeredeyeIcon {
      width: 24px;
      position: relative;
      height: 24px;
      overflow: hidden;
      flex-shrink: 0;
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
    .input1 {
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
      flex: 1;
      border-radius: var(--br-5xs);
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
    }
    .input {
      align-self: stretch;
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      justify-content: flex-start;
      gap: var(--gap-xl);
    }
    .maskedIcon {
      width: 16px;
      position: relative;
      height: 20px;
    }
    .button1 {
      position: relative;
      letter-spacing: 0.4px;
      line-height: 24px;
      text-transform: uppercase;
      font-weight: 500;
    }
    .content3 {
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: flex-start;
      gap: var(--gap-5xs);
    }
    .unstyledbutton {
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      padding: var(--padding-6xs) var(--padding-3xl);
    }
    .button {
      box-shadow: var(--light-elevation-3);
      border-radius: var(--br-5xs);
      background-color: var(--light-secondary-main);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      cursor: pointer;
    }
    .button2 {
      box-shadow: var(--light-elevation-3);
      border-radius: var(--br-5xs);
      background-color: var(--light-primary-main);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      cursor: pointer;
    }
    .action {
      align-self: stretch;
      display: flex;
      flex-direction: row;
      align-items: flex-start;
      justify-content: space-between;
      font-size: var(--light-typography-body-2-size);
      color: var(--light-background-paper);
    }
    .text {
      align-self: stretch;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: flex-start;
      gap: var(--gap-xl);
      font-size: var(--light-typography-body-1-size);
      color: var(--light-text-disabled);
    }
    .wrapper1 {
      align-self: stretch;
      flex: 1;
      background-color: var(--light-background-paper);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: var(--padding-3xs) var(--padding-126xl);
      gap: var(--gap-21xl);
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
    .registerMultiStepsAccount {
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
      font-size: var(--light-typography-h4-size);
      color: var(--light-text-primary);
      font-family: var(--light-components-input-label);
    }
  </style>
  