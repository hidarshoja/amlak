<template>
  <div>
    <div
      class="container-fluid d-flex h-100 align-items-center justify-content-center py-4 py-sm-5"
    >
      <div class="card card-body" style="max-width: 940px">
        <a
          class="position-absolute top-0 end-0 nav-link fs-sm py-1 px-2 mt-3 me-3"
          href="#"
          onclick="window.history.go(-1); return false;"
          ><i class="fi-arrow-long-right fs-base me-2"></i>برگشت</a
        >
        <div class="row mx-0 align-items-center">
          <div class="col-md-6 border-end-md p-4 p-sm-5">
            <h2 class="h3 mb-4 mb-sm-5">در سایت ما با اطمینان ثبت نام کنید.</h2>
            <ul class="list-unstyled mb-4 mb-sm-5">
              <li class="d-flex mb-2">
                <i class="fi-check-circle text-primary mt-1 me-2"></i
                ><span>افزودن و ارتقا آگهی</span>
              </li>
              <li class="d-flex mb-2">
                <i class="fi-check-circle text-primary mt-1 me-2"></i
                ><span>مدیریت لیست علاقه مندی ها</span>
              </li>
              <li class="d-flex mb-0">
                <i class="fi-check-circle text-primary mt-1 me-2"></i
                ><span>ثبت نظر</span>
              </li>
            </ul>
            <img
              class="d-block mx-auto rotate-img"
              src="/signin-modal/signup.svg"
              width="344"
              alt="Illustartion"
            />
            <div class="mt-sm-4 pt-md-3">
              ثبت نام کرده اید؟
              <a href="/auth/login">ورود به حساب کاربری</a>
            </div>
          </div>
          <div class="col-md-6 px-4 pt-2 pb-4 px-sm-5 pb-sm-5 pt-md-5">
            <a class="btn btn-outline-info w-100 mb-3" href="#"
              ><i class="fi-google fs-lg me-1"></i>ورود با اکانت گوگل</a
            ><a class="btn btn-outline-info w-100 mb-3" href="#"
              ><i class="fi-facebook fs-lg me-1"></i>ورود با اکانت فیسبوک</a
            >
            <div class="d-flex align-items-center py-3 mb-3">
              <hr class="w-100" />
              <div class="px-3">یـا</div>
              <hr class="w-100" />
            </div>
            <form class="needs-validation" novalidate>
              <div class="mb-4">
                <label class="form-label" for="signup-name"
                  >نام و نام خانوادگی</label
                >
                <input
                  class="form-control"
                  type="text"
                  id="signup-name"
                  placeholder="نام و نام خانوادگی خود را وارد کنید"
                  required
                />
              </div>
              <div class="mb-4">
                <label class="form-label" for="signup-email"
                  >پست الکترونیکی</label
                >
                <input
                  class="form-control"
                  type="email"
                  id="signup-email"
                  placeholder="ایمیل"
                  required
                />
              </div>
              <div class="mb-4">
                <label class="form-label" for="signup-password"
                  >رمز عبور
                  <span class="fs-sm text-muted">حداقل 8 کاراکتر</span></label
                >
                <div class="password-toggle">
                  <input
                    class="form-control"
                    type="password"
                    id="signup-password"
                    minlength="8"
                    required
                  />
                  <label
                    class="password-toggle-btn"
                    aria-label="Show/hide password"
                  >
                    <input class="password-toggle-check" type="checkbox" /><span
                      class="password-toggle-indicator"
                    ></span>
                  </label>
                </div>
              </div>
              <div class="mb-4">
                <label class="form-label" for="signup-password-confirm"
                  >تایید رمز عبور</label
                >
                <div class="password-toggle">
                  <input
                    class="form-control"
                    type="password"
                    id="signup-password-confirm"
                    minlength="8"
                    required
                  />
                  <label
                    class="password-toggle-btn"
                    aria-label="Show/hide password"
                  >
                    <input class="password-toggle-check" type="checkbox" /><span
                      class="password-toggle-indicator"
                    ></span>
                  </label>
                </div>
              </div>
              <div class="form-check mb-4">
                <input
                  class="form-check-input"
                  type="checkbox"
                  id="agree-to-terms"
                  required
                />
                <label class="form-check-label" for="agree-to-terms">
                  با ثبت نام در این سایت <a href="#"> شرایط</a> و
                  <a href="#">قوانین </a> سایت را قبول دارم.</label
                >
              </div>
              <button class="btn btn-primary btn-lg w-100" type="submit">
                ثبت نام
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script></script>
<style></style>
