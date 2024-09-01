<template>
  <!--begin::details View-->
  <div class="card mb-5 mb-xl-10" id="kt_profile_details_view">
    <!--begin::Card header-->
    <div class="card-header cursor-pointer">
      <!--begin::Card title-->
      <div class="card-title m-0">
        <h3 class="fw-bold m-0">Profile Details</h3>
      </div>
      <!--end::Card title-->

      <!--begin::Action-->
      <router-link
        to="/crafted/account/settings"
        class="btn btn-primary align-self-center"
        >Edit Profile</router-link
      >
      <!--end::Action-->
    </div>
    <!--begin::Card header-->

    <!--begin::Card body-->
    <div class="card-body p-9">
      <!--begin::Row-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">Full Name</label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8">
          <span class="fw-bold fs-6 text-gray-900">Max Tan</span>
        </div>
        <!--end::Col-->
      </div>
      <!--end::Row-->

      <!--begin::Input group-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">Company</label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8 fv-row">
          <span class="fw-semibold fs-6">Keenthemes</span>
        </div>
        <!--end::Col-->
      </div>
      <!--end::Input group-->

      <!--begin::Input group-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">
          Contact Phone
          <i
            class="fas fa-exclamation-circle ms-1 fs-7"
            v-tooltip
            title="Phone number must be active"
          ></i>
        </label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8 d-flex align-items-center">
          <span class="fw-bold fs-6 me-2">044 3276 454 935</span>

          <span class="badge badge-success">Verified</span>
        </div>
        <!--end::Col-->
      </div>
      <!--end::Input group-->

      <!--begin::Input group-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">Company Site</label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8">
          <a href="#" class="fw-semibold fs-6 text-dark text-hover-primary"
            >keenthemes.com</a
          >
        </div>
        <!--end::Col-->
      </div>
      <!--end::Input group-->

      <!--begin::Input group-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">
          Country
          <i
            class="fas fa-exclamation-circle ms-1 fs-7"
            v-tooltip
            title="Country of origination"
          ></i>
        </label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8">
          <span class="fw-bold fs-6 text-gray-900">Germany</span>
        </div>
        <!--end::Col-->
      </div>
      <!--end::Input group-->

      <!--begin::Input group-->
      <div class="row mb-7">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">Communication</label>
        <!--end::Label-->

        <!--begin::Col-->
        <div class="col-lg-8">
          <span class="fw-bold fs-6 text-gray-900">Email, Phone</span>
        </div>
        <!--end::Col-->
      </div>
      <!--end::Input group-->

      <!--begin::Input group-->
      <div class="row mb-10">
        <!--begin::Label-->
        <label class="col-lg-4 fw-semibold text-muted">Allow Changes</label>
        <!--begin::Label-->

        <!--begin::Label-->
        <div class="col-lg-8">
          <span class="fw-semibold fs-6">Yes</span>
        </div>
        <!--begin::Label-->
      </div>
      <!--end::Input group-->
    </div>
    <!--end::Card body-->
  </div>
  <!--end::details View-->

  <!--begin::feedback View-->
  <div class="card mb-5 mb-xl-10" id="kt_profile_details_view">
    <!--begin::Card header-->
    <div class="card-header cursor-pointer">
      <!--begin::Card title-->
      <div class="card-title m-0">
        <h3 class="fw-bold m-0">feedback</h3>
      </div>
      <!--end::Card title-->
    </div>
    <!--begin::Card header-->

    <!--begin::Card body-->
    <div class="card-body p-9">
      <!--begin::Row-->
      <div class="row mb-7">
        <!--begin::Input group-->
        <div class="fv-row">
          <!--begin::Label-->
          <label class="d-flex align-items-center fs-5 fw-semibold mb-4">
            <span class="required">Please rate</span>
          </label>
          <!--end::Label-->

          <!--begin:Options-->
          <div class="fv-row">
            <!--begin:Option-->
            <label class="d-flex flex-stack mb-5 cursor-pointer">
              <!--begin:Label-->
              <span class="d-flex align-items-center me-2">
                <!--begin:Icon-->
                <span class="symbol symbol-50px me-6">
                  <span class="symbol-label bg-light-primary">
                    <KTIcon
                      icon-name="compass"
                      icon-class="fs-1 text-primary"
                    />
                  </span>
                </span>
                <!--end:Icon-->

                <!--begin:Info-->
                <span class="d-flex flex-column">
                  <span class="fw-bold fs-6">ten points</span>
                </span>
                <!--end:Info-->
              </span>
              <!--end:Label-->

              <!--begin:Input-->
              <span class="form-check form-check-custom form-check-solid">
                <Field
                  class="form-check-input"
                  type="radio"
                  name="category"
                  value="1"
                />
              </span>
              <!--end:Input-->
            </label>
            <!--end::Option-->

            <!--begin:Option-->
            <label class="d-flex flex-stack mb-5 cursor-pointer">
              <!--begin:Label-->
              <span class="d-flex align-items-center me-2">
                <!--begin:Icon-->
                <span class="symbol symbol-50px me-6">
                  <span class="symbol-label bg-light-danger">
                    <KTIcon
                      icon-name="category"
                      icon-class="fs-1 text-danger"
                    />
                  </span>
                </span>
                <!--end:Icon-->

                <!--begin:Info-->
                <span class="d-flex flex-column">
                  <span class="fw-bold fs-6">five points</span>
                </span>
                <!--end:Info-->
              </span>
              <!--end:Label-->

              <!--begin:Input-->
              <span class="form-check form-check-custom form-check-solid">
                <Field
                  class="form-check-input"
                  type="radio"
                  name="category"
                  value="2"
                />
              </span>
              <!--end:Input-->
            </label>
            <!--end::Option-->

            <!--begin:Option-->
            <label class="d-flex flex-stack cursor-pointer">
              <!--begin:Label-->
              <span class="d-flex align-items-center me-2">
                <!--begin:Icon-->
                <span class="symbol symbol-50px me-6">
                  <span class="symbol-label bg-light-success">
                    <KTIcon icon-name="timer" icon-class="fs-1 text-success" />
                  </span>
                </span>
                <!--end:Icon-->

                <!--begin:Info-->
                <span class="d-flex flex-column">
                  <span class="fw-bold fs-6">one points</span>
                </span>
                <!--end:Info-->
              </span>
              <!--end:Label-->

              <!--begin:Input-->
              <span class="form-check form-check-custom form-check-solid">
                <Field
                  class="form-check-input"
                  type="radio"
                  name="category"
                  value="3"
                />
              </span>
              <!--end:Input-->
            </label>
            <!--end::Option-->

            <!--begin::Actions-->
            <div class="card-footer d-flex justify-content-end py-6 px-9">
              <button
                type="submit"
                id="kt_account_profile_details_submit"
                ref="submitButton1"
                class="btn btn-primary"
              >
                <span class="indicator-label"> Save </span>
                <span class="indicator-progress">
                  Please wait...
                  <span
                    class="spinner-border spinner-border-sm align-middle ms-2"
                  ></span>
                </span>
              </button>
            </div>
            <!--end::Actions-->
          </div>
          <!--end:Options-->
        </div>
        <!--end::Input group-->
      </div>
      <!--end::Row-->
    </div>
    <!--end::Card body-->
  </div>
  <!--end::feedback View-->
</template>

<script lang="ts">
import { getAssetPath } from "@/core/helpers/assets";
import { defineComponent } from "vue";
import { Field } from "vee-validate";

export default defineComponent({
  name: "account-overview",
  components: { Field },
  setup() {
    return {
      getAssetPath,
    };
  },
});
</script>
