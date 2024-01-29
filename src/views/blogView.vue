<template>
  <div>
    <div class="container mt-5 mb-md-4 py-5">
      <!-- Breadcrumb + page title-->
      <nav class="mb-3 pt-md-3" aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item">
            <a href="/">خانه</a>
          </li>
          <li class="breadcrumb-item active" aria-current="page">مقالات</li>
        </ol>
      </nav>
      <h1
        class="h3 d-flex align-items-end justify-content-between mb-4 font-vazir"
      >
        اخبار املاک
      </h1>
      <!-- Sponsored posts carousel-->
      
        <div >
          <!-- Item-->
          <div>
            <article class="row">
              <div class="col-md-7 col-lg-8 mb-lg-0 mb-3 mb-md-0">
                <a
                  class="d-block position-relative"
                  href="/detailsBlog"
                  ><span
                    class="badge bg-success position-absolute top-0 start-0 m-3 fs-sm"
                    >اسپانسر</span
                  ><img
                    class="rounded-3"
                    src="/real-estate/blog/01.jpg"
                    alt="Post image"
                /></a>
              </div>
              <div class="col-md-5 col-lg-4">
                <a class="fs-sm text-uppercase text-decoration-none" href="/detailsBlog"
                  >نکات و ترفندها</a
                >
                <h2 class="h5 pt-1">
                  <a class="nav-link" href="/detailsBlog"
                    >به دنبال مکان جدیدی هستید؟ از این زمان برای ایجاد لیست
                    دلخواه خود استفاده کنید</a
                  >
                </h2>
                <p class="d-md-none d-xl-block mb-4 line-h18">
                  لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با
                  استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و
                  مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی
                  تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای
                  کاربردی می باشد؟
                </p>
                <a
                  class="d-flex align-items-center text-decoration-none"
                  href="/detailsBlog"
                  ><img
                    class="rounded-circle"
                    src="/avatars/06.jpg"
                    width="48"
                    alt="Kristin Watson"
                  />
                  <div class="ps-2">
                    <h6 class="fs-base text-nav lh-base mb-1">
                      کریستین واتسون
                    </h6>
                    <div class="d-flex text-body fs-sm">
                      <span class="me-2 pe-1"
                        ><i class="fi-calendar-alt opacity-60 mt-n1 me-1"></i>13
                        اسفند</span
                      ><span
                        ><i class="fi-chat-circle opacity-60 mt-n1 me-1"></i>0
                        کامنت</span
                      >
                    </div>
                  </div></a
                >
              </div>
            </article>
          </div>
          <!-- Item-->
          <!-- <div>
            <article class="row">
              <div class="col-md-7 col-lg-8 mb-lg-0 mb-3 mb-md-0">
                <a
                  class="d-block position-relative"
                  href="real-estate-blog-single.html"
                  ><span
                    class="badge bg-success position-absolute top-0 start-0 m-3 fs-sm"
                    >اسپانسر</span
                  ><img
                    class="rounded-3"
                    src="/real-estate/blog/02.jpg"
                    alt="Post image"
                /></a>
              </div>
              <div class="col-md-5 col-lg-4">
                <a class="fs-sm text-uppercase text-decoration-none" href="#"
                  >اخبار صنعتی</a
                >
                <h2 class="h5 pt-1">
                  <a class="nav-link" href="real-estate-blog-single.html"
                    >بازاریابی سنتی املاک و مستغلات با وجود همه گیری همه گیر
                    است</a
                  >
                </h2>
                <p class="d-md-none d-xl-block mb-4 line-h18">
                  لورم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با
                  استفاده از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و
                  مجله در ستون و سطرآنچنان که لازم است و برای شرایط فعلی
                  تکنولوژی مورد نیاز و کاربردهای متنوع با هدف بهبود ابزارهای
                  کاربردی می باشد؟
                </p>
                <a
                  class="d-flex align-items-center text-decoration-none"
                  href="#"
                  ><img
                    class="rounded-circle"
                    src="/avatars/04.jpg"
                    width="48"
                    alt="Darrell Steward"
                  />
                  <div class="ps-2">
                    <h6 class="fs-base text-nav lh-base mb-1">دارل استیوارد</h6>
                    <div class="d-flex text-body fs-sm">
                      <span class="me-2 pe-1"
                        ><i class="fi-calendar-alt opacity-60 mt-n1 me-1"></i>27
                        بهمن</span
                      ><span
                        ><i class="fi-chat-circle opacity-60 mt-n1 me-1"></i>3
                        کامنت</span
                      >
                    </div>
                  </div></a
                >
              </div>
            </article>
          </div> -->
        </div>
      
      <!-- Carousel custom controls-->
      <div
        class="tns-carousel-controls pb-5 pt-2 mt-4 mb-lg-3"
        id="sponsored-news-controls"
      >
        <button class="me-3" type="button">
          <i class="fi-chevron-left fs-xs"></i>
        </button>
        <button type="button"><i class="fi-chevron-right fs-xs"></i></button>
      </div>
      <!-- Search bar + filters-->
      <div class="row gy-3 mb-4 pb-2">
        <div class="col-md-4 order-md-1 order-2">
          <div class="position-relative">
            <input
              class="form-control pe-5"
              type="text"
              placeholder="جستجو مقاله براساس کلمات کلیدی"
            /><i
              class="fi-search position-absolute top-50 end-0 translate-middle-y me-3"
            ></i>
          </div>
        </div>
        <div class="col-lg-6 col-md-8 offset-lg-2 order-md-2 order-1">
          <div class="row gy-3">
            <div
              class="col-6 d-flex flex-sm-row flex-column align-items-sm-center"
            >
              <label
                class="d-inline-block ms-sm-2 mb-sm-0 mb-2 text-nowrap"
                for="categories"
                ><i
                  class="fi-align-left fi-rotate mt-n1 me-2 align-middle opacity-70"
                ></i
                >دسته بندی:
              </label>
              <select class="form-select" id="categories">
                <option>همه</option>
                <option>خانه</option>
                <option>تخفیفات</option>
                <option>نکات و ترفندها</option>
                <option>اخبار صنعتی</option>
                <option>تحلیل بازار مسکن</option>
              </select>
            </div>
            <div
              class="col-6 d-flex flex-sm-row flex-column align-items-sm-center"
            >
              <label
                class="d-inline-block m-sm-2 mb-sm-0 mb-2 text-nowrap"
                for="sortby"
                ><i
                  class="fi-arrows-sort mt-n1 me-2 align-middle opacity-70"
                ></i
                >مرتب سازی براساس:
              </label>
              <select class="form-select" id="sortby">
                <option>جدیدترین</option>
                <option>قدیمی ترین</option>
                <option>پربازدید</option>
                <option>اسپانسری</option>
              </select>
            </div>
          </div>
        </div>
      </div>
      <!-- Articles grid-->
      <div
        class="row row-cols-md-2 row-cols-1 gy-md-5 gy-4 mb-lg-5 mb-4 blog-list"
      >
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><span
              class="badge bg-info position-absolute top-0 start-0 m-3 fs-sm"
              >جدید</span
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/03.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="/detailsBlog"
            >بازسازی خانه</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >10 روند شیک دکوراسیون اتاق ناهارخوری برای بهار</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="/detailsBlog"
            ><img
              class="rounded-circle"
              src="/avatars/07.jpg"
              width="48"
              alt="Cody Fisher"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">کودی فیشر</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >28 شهریور</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >0 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/04.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="#"
            >تخفیفات</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >5 پروژه جاه طلبانه آسان برای بهبود خانه شما</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="#"
            ><img
              class="rounded-circle"
              src="/avatars/03.jpg"
              width="48"
              alt="Kathryn Murphy"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">کاترین مورفی</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >26 آبان</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >4 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/05.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="#"
            >تخفیفات</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >چگونه عکاسی بدون سرنشین املاک می تواند لیست شما را ارتقا دهد؟</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="#"
            ><img
              class="rounded-circle"
              src="/avatars/06.jpg"
              width="48"
              alt="Kristin Watson"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">کریستین واتسون</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >12 آذر</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >3 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/06.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="#"
            >نکات و ترفندها</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >7 نکته برای دستیابی به حداکثر آرامش</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="#"
            ><img
              class="rounded-circle"
              src="/avatars/04.jpg"
              width="48"
              alt="Darrell Steward"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">دارل استیوارد</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >3 بهمن</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >1 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/07.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="#"
            >اخبار صنعتی</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >چگونه می توان خانه خود را با بودجه مدرن کرد</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="#"
            ><img
              class="rounded-circle"
              src="/avatars/03.jpg"
              width="48"
              alt="Kathryn Murphy"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">کاترین مورفی</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >17 اسفند</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >2 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
        <!-- Article-->
        <article class="col pb-2 pb-md-1">
          <a
            class="d-block position-relative mb-3"
            href="/detailsBlog"
            ><img
              class="d-block rounded-3"
              src="/real-estate/blog/08.jpg"
              alt="" /></a
          ><a class="fs-sm text-uppercase text-decoration-none" href="#"
            >آنالیز بازار املاک</a
          >
          <h3 class="h5 mb-2 pt-1">
            <a class="nav-link" href="/detailsBlog"
              >زمان مناسب برای کوچک سازی خانه چیست؟</a
            >
          </h3>
          <p class="mb-3">
            رم ایپسوم متن ساختگی با تولید سادگی نامفهوم از صنعت چاپ و با استفاده
            از طراحان گرافیک است. چاپگرها و متون بلکه روزنامه و مجله در ستون و
            سطرآنچنان...
          </p>
          <a class="d-flex align-items-center text-decoration-none" href="#"
            ><img
              class="rounded-circle"
              src="/avatars/07.jpg"
              width="48"
              alt="Cody Fisher"
            />
            <div class="ps-2">
              <h6 class="fs-base text-nav lh-base mb-1">کودی فیشر</h6>
              <div class="d-flex text-body fs-sm">
                <span class="me-2 pe-1"
                  ><i
                    class="fi-calendar-alt opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >18 اسفند</span
                ><span
                  ><i
                    class="fi-chat-circle opacity-70 mt-n1 me-1 align-middle"
                  ></i
                  >0 کامنت</span
                >
              </div>
            </div></a
          >
        </article>
      </div>
      <!-- Pagination-->
      <nav class="pt-4 pb-2 border-top" aria-label="Blog pagination">
        <ul class="pagination mb-0">
          <li class="page-item d-sm-none">
            <span class="page-link page-link-static">1 / 8</span>
          </li>
          <li class="page-item active d-none d-sm-block" aria-current="page">
            <span class="page-link"
              >1<span class="visually-hidden">(current)</span></span
            >
          </li>
          <li class="page-item d-none d-sm-block">
            <a class="page-link" href="#">2</a>
          </li>
          <li class="page-item d-none d-sm-block">
            <a class="page-link" href="#">3</a>
          </li>
          <li class="page-item d-none d-sm-block">...</li>
          <li class="page-item d-none d-sm-block">
            <a class="page-link" href="#">8</a>
          </li>
          <li class="page-item">
            <a class="page-link" href="#" aria-label="Next"
              ><i class="fi-chevron-right"></i
            ></a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>
