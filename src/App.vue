<template>
  <div>
    <header>
      <div class="container md:w-[1318px] w-[340px] px-10 mx-auto">
        <div
          class="header_section flex items-center justify-between py-[30px] -ml-5"
        >
          <div class="header_logo flex items-center gap-[25px]">
            <div class="-ml-10 flex md:justify-center gap-20 md:p-6">
              <img
                class="hidden max-sm:block max-md:block"
                src="./assets/icons/burger.svg"
                alt=""
              />
              <img src="./assets/icons/logo.svg" alt="" />
              <img
                class="hidden max-sm:block max-md:block"
                src="./assets/icons/phone.svg"
                alt=""
              />
            </div>
            <p class="text-sm w-[109px] max-sm:hidden max-md:hidden">
              Гофрокартон и упаковка оптом
            </p>
          </div>
          <div class="address flex gap-4 max-sm:hidden max-md:hidden md:flex">
            <img src="./assets/icons/map.svg" alt="" />
            <p class="text-sm w-[256px]">
              Московская область, Раменский р-н, Бронницы, C. Михеево
            </p>
          </div>
          <div class="phone max-sm:hidden max-md:hidden">
            <p class="font-semibold text-2xl mb-1">+7 (495) 545-47-88</p>
            <div class="flex gap-x-2.5">
              <img src="./assets/icons/clock.svg" alt="" />
              <p class="text-sm font-normal uppercase">Пн-пт: 9:00 – 18:00</p>
            </div>
          </div>
          <div class="zakazat max-sm:hidden max-md:hidden">
            <button
              class="mb-2.5 text-sm border-solid border-2 border-[#CB883A] py-2.5 px-4"
            >
              Заказать обратный звонок
            </button>
            <div class="flex gap-x-2.5 justify-end">
              <img src="./assets/icons/mail.svg" alt="" />
              <p class="text-sm text-right">zakaz@kartonika.ru</p>
            </div>
          </div>
        </div>
      </div>
      <section class="header_bottom bg-[#CB883A] text-white hidden md:block">
        <div class="container md:w-[1318px] px-10 mx-auto">
          <div
            class="md:flex-row-reverse header_bottom_section md:flex md:justify-between -ml-5 md:ml-5 items-start py-[18px] md:items-center"
          >
            <form action="" class="relative">
              <input
                type="text"
                class="rounded-full p-8 py-2 w-full md:w-[250px] outline-none text-black"
              />
              <img
                class="absolute top-1.5 right-2.5"
                src="./assets/icons/search.svg"
                alt=""
              />
            </form>
            <ul class="md:flex gap-[50px]">
              <li
                class="py-6 border-b-2 border-solid border-b-red-500 md:border-none"
              >
                <a href="#" class="md:text-xl text-sm font-bold">Продукция</a>
              </li>
              <li
                class="py-6 border-b-2 border-solid border-b-red-500 md:border-none"
              >
                <a href="#" class="md:text-xl text-sm font-bold"
                  >Наше производство</a
                >
              </li>
              <li
                class="py-6 border-b-2 border-solid border-b-red-500 md:border-none"
              >
                <a href="#" class="md:text-xl text-sm font-bold">Услуги</a>
              </li>
              <li
                class="py-6 border-b-2 border-solid border-b-red-500 md:border-none"
              >
                <a href="#" class="md:text-xl text-sm font-bold">доставка</a>
              </li>
              <li
                class="py-6 border-b-2 border-solid border-b-red-500 md:border-none"
              >
                <a href="#" class="md:text-xl text-sm font-bold">контакты</a>
              </li>
            </ul>
          </div>
        </div>
      </section>
    </header>
    <main>
      <!-- --------------------------------- INFO ------------------------------------ -->
      <section>
        <swiper-container>
          <swiper-slide
            class="bg-[url('./assets/imgs/hero_mobile.png')] md:bg-[url('./assets/imgs/hero-img.jpg')] bg-no-repeat bg-cover w-screen"
          >
            <div class="text-white bg-black/50 py-28 w-4/5 md:w-[50%] h-full">
              <div
                class="container w-[400px] md:w-[1318px] md:px-10 mx-auto px-5"
              >
                <h2
                  class="md:text-[32px] font-bold w-[376px] leading-8 md:w-[536px] text-xl md:ml-72 md:mb-1 mb-[21px]"
                >
                  СОБСТВЕННОЕ ПРОИЗВОДСТВО ГОФРОКАРТОНА,<br />
                  ТАРЫ И УПАКОВКИ
                </h2>
                <ul class="mb-7 list-disc md:ml-80 ml-5">
                  <li class="text-base mb-1">Работаем с 2008 года</li>
                  <li class="text-base mb-1">
                    Производим 80 000 м² картона в сутки
                  </li>
                  <li class="text-base mb-1">Цены на 15% ниже рыночных</li>
                </ul>
                <button
                  class="md:ml-72 mb-2.5 text-sm text-white bg-[#CB883A] py-2.5 px-4"
                >
                  Рассчитать заказ
                </button>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide
            class="bg-[url('./assets/imgs/hero_mobile.png')] md:bg-[url('./assets/imgs/hero-img.jpg')] bg-no-repeat bg-cover w-screen"
          >
            <div class="text-white bg-black/50 py-28 w-4/5 md:w-[50%] h-full">
              <div
                class="container w-[400px] md:w-[1318px] md:px-10 mx-auto px-5"
              >
                <h2
                  class="md:text-[32px] font-bold w-[376px] leading-8 md:w-[536px] text-xl md:ml-72 md:mb-1 mb-[21px]"
                >
                  СОБСТВЕННОЕ ПРОИЗВОДСТВО ГОФРОКАРТОНА,<br />
                  ТАРЫ И УПАКОВКИ
                </h2>
                <ul class="mb-7 list-disc md:ml-80 ml-5">
                  <li class="text-base mb-1">Работаем с 2008 года</li>
                  <li class="text-base mb-1">
                    Производим 80 000 м² картона в сутки
                  </li>
                  <li class="text-base mb-1">Цены на 15% ниже рыночных</li>
                </ul>
                <button
                  class="md:ml-72 mb-2.5 text-sm text-white bg-[#CB883A] py-2.5 px-4"
                >
                  Рассчитать заказ
                </button>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide
            class="bg-[url('./assets/imgs/hero_mobile.png')] md:bg-[url('./assets/imgs/hero-img.jpg')] bg-no-repeat bg-cover w-screen"
          >
            <div class="text-white bg-black/50 py-28 w-4/5 md:w-[50%] h-full">
              <div
                class="container w-[400px] md:w-[1318px] md:px-10 mx-auto px-5"
              >
                <h2
                  class="md:text-[32px] font-bold w-[376px] leading-8 md:w-[536px] text-xl md:ml-72 md:mb-1 mb-[21px]"
                >
                  СОБСТВЕННОЕ ПРОИЗВОДСТВО ГОФРОКАРТОНА,<br />
                  ТАРЫ И УПАКОВКИ
                </h2>
                <ul class="mb-7 list-disc md:ml-80 ml-5">
                  <li class="text-base mb-1">Работаем с 2008 года</li>
                  <li class="text-base mb-1">
                    Производим 80 000 м² картона в сутки
                  </li>
                  <li class="text-base mb-1">Цены на 15% ниже рыночных</li>
                </ul>
                <button
                  class="md:ml-72 mb-2.5 text-sm text-white bg-[#CB883A] py-2.5 px-4"
                >
                  Рассчитать заказ
                </button>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide
            class="bg-[url('./assets/imgs/hero_mobile.png')] md:bg-[url('./assets/imgs/hero-img.jpg')] bg-no-repeat bg-cover w-screen"
          >
            <div class="text-white bg-black/50 py-28 w-4/5 md:w-[50%] h-full">
              <div
                class="container w-[400px] md:w-[1318px] md:px-10 mx-auto px-5"
              >
                <h2
                  class="md:text-[32px] font-bold w-[376px] leading-8 md:w-[536px] text-xl md:ml-72 md:mb-1 mb-[21px]"
                >
                  СОБСТВЕННОЕ ПРОИЗВОДСТВО ГОФРОКАРТОНА,<br />
                  ТАРЫ И УПАКОВКИ
                </h2>
                <ul class="mb-7 list-disc md:ml-80 ml-5">
                  <li class="text-base mb-1">Работаем с 2008 года</li>
                  <li class="text-base mb-1">
                    Производим 80 000 м² картона в сутки
                  </li>
                  <li class="text-base mb-1">Цены на 15% ниже рыночных</li>
                </ul>
                <button
                  class="md:ml-72 mb-2.5 text-sm text-white bg-[#CB883A] py-2.5 px-4"
                >
                  Рассчитать заказ
                </button>
              </div>
            </div>
          </swiper-slide>
          <swiper-slide
            class="bg-[url('./assets/imgs/hero_mobile.png')] md:bg-[url('./assets/imgs/hero-img.jpg')] bg-no-repeat bg-cover w-screen"
          >
            <div class="text-white bg-black/50 py-28 w-4/5 md:w-[50%] h-full">
              <div
                class="container w-[400px] md:w-[1318px] md:px-10 mx-auto px-5"
              >
                <h2
                  class="md:text-[32px] font-bold w-[376px] leading-8 md:w-[536px] text-xl md:ml-72 md:mb-1 mb-[21px]"
                >
                  СОБСТВЕННОЕ ПРОИЗВОДСТВО ГОФРОКАРТОНА,<br />
                  ТАРЫ И УПАКОВКИ
                </h2>
                <ul class="mb-7 list-disc md:ml-80 ml-5">
                  <li class="text-base mb-1">Работаем с 2008 года</li>
                  <li class="text-base mb-1">
                    Производим 80 000 м² картона в сутки
                  </li>
                  <li class="text-base mb-1">Цены на 15% ниже рыночных</li>
                </ul>
                <button
                  class="md:ml-72 mb-2.5 text-sm text-white bg-[#CB883A] py-2.5 px-4"
                >
                  Рассчитать заказ
                </button>
              </div>
            </div>
          </swiper-slide>
        </swiper-container>
      </section>

      <!-- --------------------------------- TAJRIBA ------------------------------------ -->
      <section class="my-16">
        <div class="container md:w-[1318px] md:px-10 mx-auto w-[400px]">
          <div
            class="md:flex md:justify-between items-center gap-[96px] md:px-2"
          >
            <div class="mb-[42px] ml-16">
              <div class="flex items-center gap-[12px]">
                <h2 class="text-[100px] font-bold text-[#D29650]">13</h2>
                <div>
                  <h2 class="leading-9 text-[40px] font-bold w-[72px]">
                    лет опыта
                  </h2>
                </div>
              </div>
              <p class="text-xl w-[280px]">
                в производстве <br />
                и поставках гофрокартона, тары и упаковки крупными и малыми
                партиями
              </p>
            </div>
            <div class="md:grid md:grid-cols-2 gap-8 md:ml-5">
              <div
                class="ml-5 w-[360px] max-md:mb-5 border-[#D1D1D1] border-2 py-5 md:px-7 px-3"
              >
                <img class="mb-4" src="./assets/icons/calendar.svg" alt="" />
                <h3 class="mb-2.5 font-bold text-xl">ГАРАНТИЯ СРОКОВ</h3>
                <p class="text-base md:text-base md:w-80">
                  Сроки выполнения заказа от 3 дней! Возможна поставка в день
                  обращения при наличии
                </p>
              </div>
              <div
                class="ml-5 w-[360px] max-md:mb-5 border-[#D1D1D1] border-2 py-5 md:px-7 px-3"
              >
                <img class="mb-4" src="./assets/icons/money.svg" alt="" />
                <h3 class="mb-2.5 font-bold text-xl">ЛУЧШАЯ ЦЕНА НА РЫНКЕ</h3>
                <p class="text-base md:text-base md:w-[300px]">
                  3-слойный гофрокартон – от 19 руб/м2 5-слойный гофрокартон –
                  от 29 руб/м2
                </p>
              </div>
              <div
                class="ml-5 w-[360px] max-md:mb-5 border-[#D1D1D1] border-2 py-5 md:px-7 px-3"
              >
                <img
                  class="mb-4"
                  src="./assets/icons/shopping-list.svg"
                  alt=""
                />
                <h3 class="mb-2.5 font-bold text-xl">ВСЕГДА В НАЛИЧИИ</h3>
                <p class="text-base md:text-base md:w-80">
                  Временное хранение продукции на нашем складе. Возможен быстрый
                  самовывоз.
                </p>
              </div>
              <div
                class="ml-5 w-[360px] max-md:mb-5 border-[#D1D1D1] border-2 py-5 md:px-7 px-3"
              >
                <img class="mb-4" src="./assets/icons/delivery.svg" alt="" />
                <h3 class="mb-2.5 font-bold text-xl">ДОСТАВКА ДО КЛИЕНТА</h3>
                <p class="text-base md:text-base md:w-80">
                  Малыми и большими партиями, на поддонах или без (валом)
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- --------------------------------- MAXSUS TAKLIFLAR ------------------------------------ -->
      <section class="bg-[rgb(242,242,242)] pt-[57px] pb-[70px]">
        <div class="container md:w-[1318px] w-[400px] md:px-10 mx-auto">
          <div class="text-center">
            <h2
              class="font-bold text-xl md:text-3xl mb-[42px] w-[264px] md:w-[606px] mx-auto"
            >
              СПЕЦПРЕДЛОЖЕНИЯ ЭТОГО МЕСЯЦА
            </h2>
            <div
              class="md:flex items-center justify-around md:gap-[50px] grid grid-cols-2 md:px-5"
            >
              <div class="mb-10">
                <img
                  class="md:w-[203px] mb-[13px] w-[170px]"
                  src="./assets/imgs/gofokarton1.png"
                  alt=""
                />
                <h3 class="md:w-[221px] mb-2 text-sm">2-СЛОЙНЫЙ ГОФРОКАРТОН</h3>
                <p class="text-[#D29650] text-xl font-bold">от 12,5 руб/м2</p>
              </div>

              <div class="mb-10">
                <img
                  class="md:w-[203px] mb-[13px] w-[170px]"
                  src="./assets/imgs/gofrokarton2.png"
                  alt=""
                />
                <h3 class="md:w-[221px] mb-2 text-sm">
                  3-СЛОЙНЫЙ ГОФРОКАРТОН БУРЫЙ
                </h3>
                <p class="text-[#D29650] text-xl font-bold">от 12,5 руб/м2</p>
              </div>

              <div class="mb-10">
                <img
                  class="md:w-[203px] mb-[13px] w-[170px]"
                  src="./assets/imgs/gofrokarton3.png"
                  alt=""
                />
                <h3 class="md:w-[221px] mb-2 text-sm">
                  3-СЛОЙНЫЙ ГОФРОКАРТОН БЕЛЫЙ
                </h3>
                <p class="text-[#D29650] text-xl font-bold">от 12,5 руб/м2</p>
              </div>

              <div class="mb-10">
                <img
                  class="md:w-[203px] mb-[13px] w-[170px]"
                  src="./assets/imgs/gofrokarton4.png"
                  alt=""
                />
                <h3 class="md:w-[221px] mb-2 text-sm">
                  5-СЛОЙНЫЙ ГОФРОКАРТОН БЕЛЫЙ
                </h3>
                <p class="text-[#D29650] text-xl font-bold">от 12,5 руб/м2</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- --------------------------------- BIZNING MAHSULOTLAR ------------------------------------ -->
      <section class="mt-16 mb-32">
        <div class="container md:w-[1318px] w-[400px] md:px-10 px-2 mx-auto">
          <div>
            <h2 class="text-center uppercase text-3xl font-bold md:mb-16 mb-5">
              Наша продукция
            </h2>
            <div class="md:flex gap-[134px] items-center">
              <div
                class="mb-5 md:w-[490px] md:h-[624px] w-[380px] h-[355px] p-6 md:bg-[url('./assets/imgs/product1.jpg')] bg-[url('./assets/imgs/nash_produkt.png')] bg-no-repeat bg-cover"
              >
                <div
                  class="border-solid border-2 border-white md:w-full h-full"
                >
                  <p
                    class="text-[32px] font-bold md:px-20 text-center text-white md:mt-52 mt-24"
                  >
                    ЛИСТОВОЙ ГОФРОКАРТОН
                  </p>
                </div>
              </div>
              <div class="md:w-1/2 w-[380px]">
                <div class="text-left">
                  <p class="mb-5">
                    <span class="font-bold"
                      >Гофрокартон (гофрированный картон)</span
                    >– упаковочный материал, состоящий из картона для плоских
                    слоев (топлайнер) и бумаги для гофрирования (флютинг). ООО
                    «КАРТОНИКА» осуществляет производство и продает двухслойный,
                    трехслойный, пятислойный и семислойный гофрокартон различных
                    марок.
                  </p>
                  <p class="mb-11">
                    <span class="font-bold">Микрогофрокартон</span> – это
                    трехслойный гофрированный картон профилей E и F. Он имеет
                    меньшую толщину и прочность по сравнению с гофрокартоном
                    марок B и C, поэтому используется для производства упаковки
                    более легких товаров. Благодаря низкой цене и
                    привлекательному внешнему виду микрогофрокартон широко
                    используется для изготовления индивидуальной и подарочной
                    упаковки.
                  </p>
                  <div>
                    <h3 class="font-bold mb-[16px] text-sm md:text-lg">
                      Популярные размеры (всегда в наличии):
                    </h3>
                    <table class="table-fixed mb-20 w-full">
                      <thead class="bg-[#DEDEDE]">
                        <tr>
                          <th class="py-2 pl-5 text:sm">Тип картона</th>
                          <th class="py-2 pl-5 text:sm">Размер</th>
                          <th class="py-2 pl-5 text:sm">Цена</th>
                        </tr>
                      </thead>
                      <tbody>
                        <tr>
                          <td
                            rowspan="4"
                            class="text-xs md:text-base md:pl-5 font-bold text-[14px] w-[126px]"
                          >
                            Трехслойный Гофрокартон Т-21
                          </td>
                          <td
                            class="text-xs md:text-base border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2"
                          >
                            лист 1050 х 2000 мм
                          </td>
                          <td
                            class="text-xs md:text-base border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2"
                          >
                            от 39 руб./лист
                          </td>
                        </tr>
                        <tr>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            лист 1200 х 800 мм
                          </td>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            от 18 руб./лист
                          </td>
                        </tr>
                        <tr>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            лист 1050 х 2500 мм
                          </td>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            от 47 руб./лист
                          </td>
                        </tr>
                        <tr>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            лист 1200 х 1000 мм
                          </td>
                          <td
                            class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-2 text-xs md:text-base"
                          >
                            от 25 руб./лист
                          </td>
                        </tr>
                      </tbody>
                    </table>
                  </div>
                </div>

                <div class="flex gap-[18px] -ml-1 md:ml-1">
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Подробнее
                  </button>
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Заказать
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- --------------------------------- BIZNING MAHSULOTLAR 2 ------------------------------------ -->

      <section class="mt-16 md:mb-32 mb-14 bg-[#F2F2F2] py-20">
        <div class="container md:w-[1318px] px-10 mx-auto">
          <div
            class="flex gap-10 md:gap-[134px] items-center max-md:flex-col-reverse"
          >
            <div class="md:w-1/2 w-[380px] text-left">
              <p class="mb-5">
                <span class="font-bold">Картон Т21-22</span>
                различных размеров имеется в наличии, а так же может быть
                изготовлен под заказ различной длины (25, 50, 100м). Двухслойный
                гофрокартон в рулонах является одним из наиболее часто
                используемых защитных материалов при проведении ремонтных работ,
                а так же для обеспечения безопасности товаров при их
                транспортировке.
              </p>
              <span class="font-bold">Идеально подходит:</span>
              <ul class="list-disc ml-5 mb-5">
                <li>
                  Для защиты мебели и других предметов интерьера во время
                  переезда или хранения;
                </li>
                <li>
                  Для защиты любых напольных покрытий как деревянных, так и
                  керамических во время ремонта. В отличии от обычной бумаги
                  второй гофрированный слой дополнительно защищает покрытие от
                  механических воздействий и повреждений. В отличии от обычной
                  пленки не создает парниковый эффект.
                </li>
                <li>
                  Для защиты хрупких предметов, таких как стекло, зеркала и тд.
                </li>
                <li>
                  Для защиты окрашенных поверхностей от царапин и других
                  повреждений;
                </li>
                <li>Для упаковки товаров и посылок</li>
              </ul>
              <div>
                <h3 class="font-bold mb-[16px] text-sm md:text-lg">
                  Популярные размеры (всегда в наличии):
                </h3>
                <table class="table-fixed mb-10 w-[100%]">
                  <thead class="bg-[#DEDEDE]">
                    <tr>
                      <th class="py-2 pl-5 md:pl-14">Тип картона</th>
                      <th class="py-2 md:pl-5">Размер</th>
                      <th class="py-2 pl-5">Цена</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td
                        rowspan="4"
                        class="font-bold text-[14px] md:w-[126px] md:text-lg text-center"
                      >
                        Двухслойный гофрокартон
                      </td>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 text-xs md:text-base"
                      >
                        ролик 1050мм х 100м
                      </td>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-5 text-xs md:text-base"
                      >
                        от 1850 руб./шт
                      </td>
                    </tr>
                    <tr>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 text-xs md:text-base"
                      >
                        ролик 1250мм х 100м
                      </td>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-5 text-xs md:text-base"
                      >
                        от 2200 руб./шт
                      </td>
                    </tr>
                    <tr>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 text-xs md:text-base"
                      >
                        ролик 1400мм х 100м
                      </td>
                      <td
                        class="border-b-2 border-b-solid border-b-[#DEDEDE] py-2 md:px-5 pl-5 text-xs md:text-base"
                      >
                        от 2500 руб./шт
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
              <div class="flex gap-[18px]">
                <button
                  class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                >
                  Подробнее
                </button>
                <button
                  class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                >
                  Заказать
                </button>
              </div>
            </div>
            <div
              class="md:w-[490px] md:h-[624px] w-[380px] h-[355px] p-6 bg-[url('./assets/imgs/product2.jpg')]"
            >
              <div
                class="border-solid border-2 border-white w-full h-full text-white text-center"
              >
                <p
                  class="text-[32px] font-bold md:px-20 text-center mt-24 md:mt-52"
                >
                  ЛИСТОВОЙ ГОФРОКАРТОН
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- --------------------------------- BIZNING MAHSULOTLAR 3 ------------------------------------ -->

      <section class="md:mt-16 mb-32">
        <div class="container md:w-[1318px] w-[400px] md:px-10 mx-auto">
          <div>
            <div class="md:flex gap-[134px] items-center">
              <div
                class="md:w-[490px] ml-2 max-md:mb- w-96 md:h-[468px] h-[250px] mb-8 p-6 bg-[url('./assets/imgs/product3.jpg')] bg-no-repeat bg-cover"
              >
                <div
                  class="border-solid border-2 border-white w-full h-full text-white"
                >
                  <p
                    class="text-[32px] font-bold md:px-20 text-center md:mt-40 mt-14"
                  >
                    ЛИСТОВОЙ ГОФРОКАРТОН
                  </p>
                </div>
              </div>
              <div class="text-left md:w-[594px] w-96 px-2">
                <p class="mb-5">
                  <span class="font-bold">Гофротара</span>– это тара и упаковка,
                  изготовленная из гофрокартона. Благодаря невысокой цене и
                  достаточно простой конструкции гофротара широко используется
                  для упаковки как промышленных товаров, так и пищевой
                  продукции. ООО «КАРТОНИКА» осуществляет
                  изготовление/производство и продажу различных видов гофротары.
                  Среди выпускаемой продукции гофроящики, гофрокороба (коробки),
                  гофролотки и другая картонная тара, а также гофроупаковка с
                  нанесением печати.
                </p>
                <p class="mb-5">
                  В зависимости от сферы использования наша гофротара
                  разделяется на следующие виды:
                </p>
                <ul class="list-disc ml-10 mb-16">
                  <li>транспортная гофротара;</li>
                  <li>производственная гофротара;</li>
                  <li>потребительская гофротара</li>
                </ul>

                <div class="flex gap-[18px]">
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Подробнее
                  </button>
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Заказать
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- --------------------------------- BIZNING MAHSULOTLAR 4 ------------------------------------ -->
      <section class="mt-16 mb-32 bg-[#F2F2F2] py-20">
        <div class="container md:w-[1318px] w-[400px] px-10 mx-auto">
          <div>
            <div
              class="flex md:gap-[134px] gap-8 items-center max-md:flex-col-reverse"
            >
              <div class="md:w-1/2 w-[380px] text-left">
                <p class="mb-5">
                  <span class="font-bold"
                    >Упаковочные изделия из гофрокартона</span
                  >
                  - применяются в качестве дополнительной упаковки продукции с
                  целью их защиты от механических повреждений.
                </p>
                <p class="mb-5">
                  Мы производим гофро изделия, предназначенные для использования
                  в различных отраслях: мебельное производство, строительные
                  материалы, пищевое производство, электронная и бытовая
                  техника, химическое производство и другие.
                </p>
                <p class="mb-5">
                  Понимая, что каждое производство имеет свою специфику и
                  требования к упаковке везде разные, мы обеспечиваем
                  индивидуальный подход к решению задач по упаковке для каждого
                  заказчика. Наши специалисты внимательно изучат вашу нишу и с
                  учетом всех нюансов предложат вам оптимальные варианты
                  упаковочных материалов, чтобы ваша продукция в идеальном виде
                  доходила до конечного потребителя.
                </p>

                <div class="flex gap-[18px]">
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Подробнее
                  </button>
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-3 md:px-12 px-[45px]"
                  >
                    Заказать
                  </button>
                </div>
              </div>
              <div
                class="md:w-[490px] md:h-[468px] w-[380px] h-[355px] bg-no-repeat bg-cover p-6 bg-[url('./assets/imgs/product4.jpg')]"
              >
                <div
                  class="border-solid border-2 border-white w-full h-full text-white"
                >
                  <p
                    class="text-[32px] font-bold md:px-20 text-center mt-24 md:mt-40"
                  >
                    УПАКОВОЧНЫЕ ИЗДЕЛИЯ
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- -------------------------- Locatsiya ------------------------------ -->

      <section
        class="w-full bg-[url('./assets/imgs/hero.png')] bg-no-repeat bg-cover h-full mb-[70px]"
      >
        <div class="container md:w-[1318px] w-[400px] mx-auto md:px-5">
          <div class="md:flex items-center text-white gap-28 justify-between">
            <div class="py-32 px-5">
              <h2 class="font-bold text-3xl md:mb-16 mb-10">КОРОТКО О НАС</h2>
              <ul class="list-disc md:w-[454px] text-base md:text-lg">
                <li class="md:mb-10 mb-5">
                  13 лет успешной работы на рынке гофроиндустрии
                </li>
                <li class="md:mb-10 mb-5">
                  Огромный опыт в разработке и производстве упаковки из
                  гофрокартона
                </li>
                <li class="md:mb-10 mb-5">Более 120 постоянных покупателей</li>
                <li class="md:mb-10 mb-5">
                  Огромный ассортимент выпускаемой продукции
                </li>
                <li class="md:mb-10 mb-5">
                  Работаем по ГОСТ и ТУ, наш картон и гофроупаковка
                  соответствуют требованиям ISO 9001
                </li>
              </ul>
            </div>
            <div>
              <iframe
                class="md:w-[709px] md:h-[752px] h-[615px] w-[393px]"
                src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d2919.6397747177593!2d69.20228991947826!3d41.27298750286448!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2s!4v1715798645195!5m2!1sen!2s"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>
        </div>
      </section>

      <!-- ----------------------------- BIZNING SERTIFIKATLARIMIZ --------------------------------- -->
      <section class="container md:w-[1318px] w-[340px] px-10 mx-auto mb-32">
        <h3 class="text-center text-2xl font-bold mb-16">НАШИ СЕРТИФИКАТЫ</h3>
        <swiper-container>
          <swiper-slide class="flex justify-center gap-16">
            <img
              class="hidden md:block"
              src="./assets/imgs/sertifikat2.png"
              alt=""
            />
            <img
              class="hidden md:block"
              src="./assets/imgs/sertifikat.png"
              alt=""
            />
            <img src="./assets/imgs/sertifikat2.png" alt="" />
          </swiper-slide>
          <swiper-slide class="md:hidden">
            <img src="./assets/imgs/sertifikat.png" alt="" />
          </swiper-slide>
          <swiper-slide class="md:hidden">
            <img src="./assets/imgs/sertifikat2.png" alt="" />
          </swiper-slide>
        </swiper-container>
        <!-- <div class="md:flex gap-20 justify-center mb-[97px]">
            </div> -->
      </section>

      <!-- ------------------------------ SLIDER ------------------------------ -->
      <div class="slider">
        <div class="slide-track">
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/1.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/2.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/3.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/4.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/5.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/6.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/7.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/1.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/2.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/3.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/4.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/5.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/6.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
          <div class="slide">
            <img
              src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/557257/7.png"
              height="100"
              width="250"
              alt=""
            />
          </div>
        </div>
      </div>
      <!-- --------------------- EMAIL ---------------------------------- -->
      <section class="my-20">
        <div class="container md:w-[1318px] w-[400px] md:px-10 px-2 mx-auto">
          <div class="text-center">
            <h3 class="md:text-[32px] text-2xl uppercase font-bold mb-[39px]">
              Отвечаем на Ваши вопросы, принимаем предложения
            </h3>
            <div class="md:flex justify-center gap-[30px]">
              <form class="flex flex-col md:w-[386px] w-[375px]" action="">
                <input
                  class="focus:outline-none border-2 border-solid hover:border-[#CB883A] border-[#BCBCBC] mb-4 py-4 px-5"
                  type="text"
                  name=""
                  id=""
                  placeholder="Имя"
                />
                <input
                  class="focus:outline-none border-2 border-solid hover:border-[#CB883A] border-[#BCBCBC] mb-4 py-4 px-5"
                  type="text"
                  name=""
                  id=""
                  placeholder="Телефон"
                />
                <input
                  class="focus:outline-none border-2 border-solid hover:border-[#CB883A] border-[#BCBCBC] mb-4 py-4 px-5"
                  type="text"
                  name=""
                  id=""
                  placeholder="E-mail"
                />
                <input
                  class="focus:outline-none border-2 border-solid hover:border-[#CB883A] border-[#BCBCBC] mb-4 py-4 px-5"
                  type="text"
                  name=""
                  id=""
                  placeholder="Организация"
                />
              </form>
              <div class="flex flex-col">
                <textarea
                  class="focus:outline-none resize-none md:w-[489px] w-[375px] md:h-[228px] h-[196px] border-2 border-solid border-[#BCBCBC] mb-4 md:py-4 px-5 text-[#7F7F7F]"
                  name=""
                  id=""
                >
Введите текст сообщения</textarea
                >
                <div class="md:flex items-center md:justify-between">
                  <form
                    class="my-7 flex justify-center items-center gap-5"
                  >
                    <img src="../src/assets/icons/Vector.svg" alt="" />
                    <button onclick="focusInput()">Прикрепить файл</button>
                    <input
                      class="hidden"
                      placeholder="Прикрепить файл"
                      type="file"
                      id="input"
                    />
                  </form>
                  <button
                    class="mb-2.5 text-lg font-medium border-2 border-solid border-[#CB883A] hover:text-white hover:bg-[#CB883A] py-2 md:px-12 px-[130px]"
                  >
                    Подробнее
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <!-- ------------------------------- FOOTER ------------------------------------------ -->
    <footer class="bg-[#595959] pt-[58px] md:pb-[70px] pb-10">
      <div class="container md:w-[1318px] w-[400px] md:px-10 px-3 mx-auto">
        <div class="md:flex justify-evenly">
          <div class="text-white flex md:gap-[123px] gap-5 mb-7">
            <ul>
              <li class="mb-5">
                <h2 class="font-bold uppercase">Продукция</h2>
              </li>
              <li class="mb-5"><a href="#">Гофрокартон листовой</a></li>
              <li class="mb-5"><a href="#">Гофрокартон в рулонах</a></li>
              <li class="mb-5"><a href="#">Гофротара</a></li>
              <li class="mb-5"><a href="#">Упаковочные изделия</a></li>
            </ul>
            <ul>
              <li class="mb-5">
                <h2 class="font-bold uppercase">Наше производство</h2>
              </li>
              <li class="mb-5">
                <a class="uppercase font-bold" href="#">Услуги</a>
              </li>
              <li class="mb-5">
                <a class="uppercase font-bold" href="#">доставка</a>
              </li>
              <li class="mb-5">
                <a class="uppercase font-bold" href="#">контакты</a>
              </li>
            </ul>
          </div>
          <div class="text-white flex flex-col items-center">
            <div class="md:flex gap-[58px] md:mb-[76px] mb-10">
              <div>
                <p class="font-semibold text-2xl md:mb-1 mb-5">
                  +7 (495) 545-47-88
                </p>
                <div class="flex gap-x-2.5 mb-7 max-md:ml-7">
                  <img src="./assets/icons/clock.svg" alt="" />
                  <p class="text-sm font-normal uppercase">
                    Пн-пт: 9:00 – 18:00
                  </p>
                </div>
              </div>
              <div class="zakazat">
                <button
                  class="md:mb-2.5 mb-7 text-sm border-solid border-2 border-[#CB883A] py-2.5 px-4"
                >
                  Заказать обратный звонок
                </button>
                <div class="flex gap-x-2.5 md:justify-end ml-7">
                  <img src="./assets/icons/mail.svg" alt="" />
                  <p class="text-sm text-right">zakaz@kartonika.ru</p>
                </div>
              </div>
            </div>
            <div class="address flex gap-4 w-72 md:w-80">
              <img src="./assets/icons/map.svg" alt="" />
              <p class="text-sm">
                Московская область, Раменский р-н, Бронницы, C. Михеево
              </p>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
      
</script>