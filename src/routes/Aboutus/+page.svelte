<script>
    import Footer from "../../Components/Footer.svelte";
    import Header from "../../Components/Header.svelte";
</script>

<Header />
<main>
    <div>
        <!-- About us -->
        <div
            class="flex flex-row justify-center pt-[224px] gap-[138px] pb-[128px] sm:flex-col sm:items-center md:flex-col md:items-center lg:flex-col lg:items-center xl:flex-row "
        >
            <div>
                <p class="font-sans text-[18px] font-medium leading-[32px]">
                    About us
                </p>
                <p
                    class="font-sans text-[54px] font-semibold leading-[74px] max-w-[595px] text-[#282938] pt-[8px] pb-[31px]"
                >
                    Our designs solve problems
                </p>
                <p
                    class="font-sans text-[16px] font-normal leading-[28px] max-w-[595px] text-[#282938]/[0.699999988079071]"
                >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam.
                </p>
            </div>
            <div>
                <img
                    src="/src/lib/assets/people-sitting-indoors-3184360.png"
                    alt=""
                />
            </div>
        </div>
        <!-- Who we are -->
        <div
            class="flex flex-col m-auto max-w-[1280px] bg-[#F4F5F5] pt-[80px] sm:flex-col md:items-center md:flex-col md:items-center lg:flex-col lg:items-center xl:flex-col xl:items-start"
        >
            <p
                class="pl-[79px] font-sans text-[16px] font-medium leading-[28px] text-left"
            >
                Who we are
            </p>
            <div class="flex flex-row pl-[79px] gap-[61px]">
                <div>
                    <p
                        class="font-sans text-[38px] font-semibold leading-[56px]"
                    >
                        Goal focussed
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor incididunt ut labore et dolore
                        magna aliqua. Ut enim ad minim veniam, quis nostrud
                        exercitation ullamco laboris nisi ut aliquip ex ea
                        commodo consequat.
                    </p>
                </div>
                <!-- 2nd col -->
                <div>
                    <p
                        class="font-sans text-[38px] font-semibold leading-[56px]"
                    >
                        Continuous improvement
                    </p>
                    <p
                        class="pr-[109px] font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor incididunt ut labore et dolore
                        magna aliqua. Ut enim ad minim veniam, quis nostrud
                        exercitation ullamco laboris nisi ut aliquip ex ea
                        commodo consequat.
                    </p>
                </div>
            </div>
            <img
                class="pt-[80px]"
                src="/src/lib/assets/man-in-blue-jacket-looking-at-white-board-7413916.png"
                alt=""
            />
        </div>
    </div>
    <!-- The process we follow -->
    <div class="flex flex-col items-center pt-[128px] pb-[128px]">
        <div>
            <p class="font-sans text-[48px] font-semibold leading-[64px]">
                The process we follow
            </p>
        </div>
        <!-- The process we follow :4 divs -->
        <div
            class="flex gap-[56px] pt-[48px] sm:flex-col md:items-center md:flex-col md:items-center lg:flex-col lg:items-center xl:flex-row"
        >
            <!-- Div 1 -->
            <div>
                <div class="flex flex-row items-center gap-[24px]">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        fill="none"
                    >
                        <circle cx="12" cy="12" r="12" fill="#2405F2" />
                    </svg>
                    <!-- Dotted Line -->
                    <svg
                        width="224"
                        height="3"
                        viewBox="0 0 224 3"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <line
                            opacity="0.4"
                            x1="1"
                            y1="1.36621"
                            x2="223"
                            y2="1.36621"
                            stroke="#2405F2"
                            stroke-width="2"
                            stroke-linecap="round"
                            stroke-dasharray="2 8"
                        />
                    </svg>
                </div>
                <p
                    class="font-sans text-[24px] font-medium leading-[36px] pt-[43.63px]"
                >
                    Planning
                </p>
                <p
                    class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[272px]"
                >
                    Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
                </p>
            </div>
            <div>
                <!-- Div 2 -->
                <div>
                    <div class="flex flex-row items-center gap-[24px]">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="24"
                            height="24"
                            viewBox="0 0 24 24"
                            fill="none"
                        >
                            <circle cx="12" cy="12" r="12" fill="#2405F2" />
                        </svg>
                        <!-- Dotted Line -->
                        <svg
                            width="224"
                            height="3"
                            viewBox="0 0 224 3"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <line
                                opacity="0.4"
                                x1="1"
                                y1="1.36621"
                                x2="223"
                                y2="1.36621"
                                stroke="#2405F2"
                                stroke-width="2"
                                stroke-linecap="round"
                                stroke-dasharray="2 8"
                            />
                        </svg>
                    </div>
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pt-[43.63px]"
                    >
                        Conception
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[272px]"
                    >
                        Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
                    </p>
                </div>
            </div>
            <div>
                <!-- Div 3 -->
                <div>
                    <div class="flex flex-row items-center gap-[24px]">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="24"
                            height="24"
                            viewBox="0 0 24 24"
                            fill="none"
                        >
                            <circle cx="12" cy="12" r="12" fill="#2405F2" />
                        </svg>
                        <!-- Dotted Line -->
                        <svg
                            width="224"
                            height="3"
                            viewBox="0 0 224 3"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <line
                                opacity="0.4"
                                x1="1"
                                y1="1.36621"
                                x2="223"
                                y2="1.36621"
                                stroke="#2405F2"
                                stroke-width="2"
                                stroke-linecap="round"
                                stroke-dasharray="2 8"
                            />
                        </svg>
                    </div>
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pt-[43.63px]"
                    >
                        Design
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[272px]"
                    >
                        Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
                    </p>
                </div>
            </div>
            <div>
                <!-- Div 4 -->
                <div>
                    <div class="flex flex-row items-center gap-[24px]">
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            width="24"
                            height="24"
                            viewBox="0 0 24 24"
                            fill="none"
                        >
                            <circle cx="12" cy="12" r="12" fill="#2405F2" />
                        </svg>
                        <!-- Dotted Line -->
                        <svg
                            width="224"
                            height="3"
                            viewBox="0 0 224 3"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <line
                                opacity="0.4"
                                x1="1"
                                y1="1.36621"
                                x2="223"
                                y2="1.36621"
                                stroke="#2405F2"
                                stroke-width="2"
                                stroke-linecap="round"
                                stroke-dasharray="2 8"
                            />
                        </svg>
                    </div>
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pt-[43.63px]"
                    >
                        Development
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[272px]"
                    >
                        Lorem ipsum dolor sit amet, consetetur sadipscing elitr.
                    </p>
                </div>
            </div>
        </div>
    </div>
    <!-- Our Mission  -->
    <div class="flex flex-col">
        <div
            class="flex flex-row bg-[#EEF4FA] pt-[128px] items-center justify-center gap-[140px] sm:flex-col md:flex-col lg:flex-row xl:flex-row"
        >
            <div class="flex flex-col justify-center">
                <p class="font-sans text-[16px] font-medium leading-[28px]">
                    Our Mission
                </p>
                <p class="font-sans text-[38px] font-semibold leading-[56px]">
                    Inspire, Innovate, Share
                </p>
                <p
                    class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[623px]"
                >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>
            </div>
            <img
                src="/src/lib/assets/a-man-standing-in-an-office-7792811.png"
                alt=""
            />
        </div>
        <div
            class="flex flex-row bg-[#EEF4FA] pt-[128px] items-center justify-center gap-[140px] pb-[128px] sm:flex-col md:flex-col lg:flex-row xl:flex-row"
        >
            <img
                src="/src/lib/assets/photo-of-women-at-the-meeting-3810789.png"
                alt=""
                class=""
            />

            <div class="flex flex-col justify-center">
                <p class="font-sans text-[16px] font-medium leading-[28px]">
                    Our Vision
                </p>
                <p class="font-sans text-[38px] font-semibold leading-[56px]">
                    Laser focus
                </p>
                <p
                    class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071] max-w-[623px]"
                >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                </p>
            </div>
        </div>
        <!-- The benefits of working with us -->
        <div class="flex flex-col items-center pt-[128px]">
            <!-- <div> -->
            <p
                class="font-sans text-[48px] font-semibold leading-[64px] w-[630px] text-center"
            >
                The benefits of working with us
            </p>
            <!-- </div> -->
            <!-- 3 cards -->
            <div class="flex flex-row pt-[48px] gap-[32px]">
                <div
                    class="bg-[#F4F6FC] pt-[50px] pl-[48px] pb-[48px] pr-[32.61px]"
                >
                    <!-- svg -->
                    <svg
                        width="32"
                        height="32"
                        viewBox="0 0 32 32"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            d="M24.3444 5.46387C24.3444 4.71312 24.0514 4.00637 23.5204 3.47537L20.869 0.824C20.3454 0.300313 19.602 0 18.8623 0H18.7012V5.625H24.3444L24.3444 5.46387Z"
                            fill="#2405F2"
                        />
                        <path
                            d="M17.1211 19.3461C17.3005 18.8013 17.6136 18.2941 18.0219 17.8831L24.3696 11.561V7.5H17.7821C17.2639 7.5 16.875 7.08069 16.875 6.5625V0H2.8125C1.26163 0 0 1.26163 0 2.8125V29.1875C0 30.7384 1.26163 32 2.8125 32H21.5321C23.0829 32 24.3696 30.7384 24.3696 29.1875V22.1906L23.3393 23.1958C22.9219 23.6096 22.433 23.9108 21.8818 24.0949L18.9009 25.0901L18.4468 25.1148C17.696 25.1148 16.9856 24.7495 16.5443 24.1379C16.1067 23.5291 15.9877 22.7399 16.2257 22.0268L17.1211 19.3461ZM4.6875 16.875H14.0321C14.5503 16.875 14.9696 17.2943 14.9696 17.8125C14.9696 18.3307 14.5503 18.75 14.0321 18.75H4.6875C4.16931 18.75 3.75 18.3307 3.75 17.8125C3.75 17.2943 4.16931 16.875 4.6875 16.875ZM3.75 14.0625C3.75 13.5443 4.16931 13.125 4.6875 13.125H14.0321C14.5503 13.125 14.9696 13.5443 14.9696 14.0625C14.9696 14.5807 14.5503 15 14.0321 15H4.6875C4.16931 15 3.75 14.5807 3.75 14.0625ZM3.75 21.5625C3.75 21.0443 4.16931 20.625 4.6875 20.625H14.0321C14.5503 20.625 14.9696 21.0443 14.9696 21.5625C14.9696 22.0807 14.5503 22.5 14.0321 22.5H4.6875C4.16931 22.5 3.75 22.0807 3.75 21.5625ZM17.7821 26.25C18.3003 26.25 18.7196 26.6693 18.7196 27.1875C18.7196 27.7057 18.3003 28.125 17.7821 28.125H12.1571C11.6389 28.125 11.2196 27.7057 11.2196 27.1875C11.2196 26.6693 11.6389 26.25 12.1571 26.25H17.7821ZM4.6875 11.25C4.16931 11.25 3.75 10.8307 3.75 10.3125C3.75 9.79431 4.16931 9.375 4.6875 9.375H17.7821C18.3003 9.375 18.7196 9.79431 18.7196 10.3125C18.7196 10.8307 18.3003 11.25 17.7821 11.25H4.6875Z"
                            fill="#2405F2"
                        />
                        <path
                            d="M18.819 20.1758L18.0034 22.6227C17.8812 22.9893 18.23 23.338 18.5965 23.2155L21.042 22.3988L18.819 20.1758Z"
                            fill="#2405F2"
                        />
                        <path
                            d="M26.1011 12.457L19.9268 18.6313L22.5896 21.2942C23.9851 19.8984 26.7004 17.1827 28.7636 15.1195L26.1011 12.457Z"
                            fill="#2405F2"
                        />
                        <path
                            d="M31.4496 9.76703C31.1201 9.43559 30.6348 9.24609 30.1203 9.24609C29.6057 9.24609 29.1205 9.43559 28.7891 9.76797L27.4268 11.1303L30.0891 13.7927C30.8349 13.0468 31.3504 12.5313 31.4516 12.4302C32.1839 11.6968 32.1838 10.5022 31.4496 9.76703Z"
                            fill="#2405F2"
                        />
                    </svg>

                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pt-[26px] pb-[12px]"
                    >
                        Customize with ease
                    </p>
                    <p
                        class="max-w-[324.079px] font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor incididunt ut labore et dolore
                        magna aliqua ut enim.
                    </p>
                </div>
                <div>
                    <div
                        class="bg-[#F4F6FC] pt-[50px] pl-[48px] pb-[48px] pr-[32.61px]"
                    >
                        <!-- svg -->
                        <svg
                            width="32"
                            height="32"
                            viewBox="0 0 32 32"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <g clip-path="url(#clip0_126_242)">
                                <path
                                    d="M2.41529 9.0443L9.04445 2.41514L7.93947 1.31015C6.11183 -0.517488 3.13795 -0.517488 1.31055 1.3104C0.42505 2.19565 -0.0625 3.37266 -0.0625 4.62486C-0.0625 5.87681 0.42505 7.05406 1.31055 7.93932L2.41529 9.0443Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M3.74121 10.3704L6.39283 7.71875L10.1924 11.5183L7.54078 14.1699L3.74121 10.3704Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M7.71875 6.39283L10.3704 3.74121L14.1699 7.54053L11.5183 10.1922L7.71875 6.39283Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M22.8237 28.1272C22.8237 28.1275 22.8237 28.1275 22.8235 28.1275L22.3867 28.5645L30.6516 31.8704C30.7644 31.9155 30.8823 31.9375 30.9995 31.9375C31.2437 31.9375 31.4834 31.8421 31.6626 31.6629C31.9278 31.3977 32.0093 31 31.8701 30.6516L28.5642 22.3867L22.8237 28.1272Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M17.7051 24.3342L20.3567 21.6826L23.4866 24.8128L20.835 27.4644L17.7051 24.3342Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M21.6826 20.3569L24.3342 17.7051L27.4644 20.8352L24.8128 23.4868L21.6826 20.3569Z"
                                    fill="#2405F2"
                                />
                                <path
                                    d="M8.05129 25.1497C7.68508 25.5157 7.68508 26.1094 8.05129 26.4754L10.482 28.9061L7.72511 31.6629C7.35915 32.0291 6.7654 32.0291 6.39943 31.6629L0.212159 25.4756C-0.154053 25.1097 -0.154053 24.5159 0.212159 24.15L24.15 0.212159C24.5159 -0.154053 25.1097 -0.154053 25.4756 0.212159L31.6629 6.39918C31.846 6.58229 31.9376 6.82228 31.9376 7.06227C31.9376 7.30202 31.846 7.54201 31.6629 7.72511L28.9061 10.482L25.5916 7.16725C25.2254 6.80104 24.6319 6.80104 24.2657 7.16725C23.8997 7.53346 23.8997 8.12697 24.2657 8.49318L27.5801 11.8076L25.4864 13.9016L23.0557 11.4707C22.6897 11.1048 22.096 11.1048 21.7298 11.4707C21.3638 11.8369 21.3638 12.4304 21.7298 12.7967L24.1605 15.2273L22.0667 17.3213L18.7522 14.0066C18.386 13.6407 17.7925 13.6407 17.4263 14.0066C17.0603 14.3728 17.0603 14.9663 17.4263 15.3326L20.7408 18.647L18.647 20.741L16.2163 18.3103C15.8501 17.9441 15.2566 17.9441 14.8904 18.3103C14.5244 18.6763 14.5244 19.2698 14.8904 19.636L17.3211 22.0667L15.2273 24.1607L11.9129 20.846C11.5467 20.48 10.9531 20.48 10.5869 20.846C10.221 21.2122 10.221 21.8057 10.5869 22.1719L13.9014 25.4864L11.8076 27.5804L9.37697 25.1497C9.01101 24.7835 8.41725 24.7835 8.05129 25.1497Z"
                                    fill="#2405F2"
                                />
                            </g>
                            <defs>
                                <clipPath id="clip0_126_242">
                                    <rect width="32" height="32" fill="white" />
                                </clipPath>
                            </defs>
                        </svg>

                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] pt-[26px] pb-[12px]"
                        >
                            Customize with ease
                        </p>
                        <p
                            class="max-w-[324.079px] font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                        >
                            Lorem ipsum dolor sit amet, consectetur adipiscing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua ut enim.
                        </p>
                    </div>
                </div>
                <div>
                    <div
                        class="bg-[#F4F6FC] pt-[50px] pl-[48px] pb-[48px] pr-[32.61px]"
                    >
                        <!-- svg -->
                        <svg
                            width="32"
                            height="28"
                            viewBox="0 0 32 28"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M16 10.8749C19.003 10.8749 21.4374 8.44047 21.4374 5.43745C21.4374 2.43443 19.003 0 16 0C12.9969 0 10.5625 2.43443 10.5625 5.43745C10.5625 8.44047 12.9969 10.8749 16 10.8749Z"
                                fill="#2405F2"
                            />
                            <path
                                d="M27 10.8749C28.8984 10.8749 30.4374 9.33593 30.4374 7.43747C30.4374 5.53901 28.8984 4 27 4C25.1015 4 23.5625 5.53901 23.5625 7.43747C23.5625 9.33593 25.1015 10.8749 27 10.8749Z"
                                fill="#2405F2"
                            />
                            <path
                                d="M4.99997 10.8749C6.89843 10.8749 8.43744 9.33593 8.43744 7.43747C8.43744 5.53901 6.89843 4 4.99997 4C3.10151 4 1.5625 5.53901 1.5625 7.43747C1.5625 9.33593 3.10151 10.8749 4.99997 10.8749Z"
                                fill="#2405F2"
                            />
                            <path
                                d="M8.3868 13.9613C7.03369 12.8527 5.80826 12.9995 4.24371 12.9995C1.90373 12.9995 0 14.892 0 17.2176V24.0431C0 25.0531 0.824368 25.8744 1.83811 25.8744C6.21469 25.8744 5.68745 25.9535 5.68745 25.6856C5.68745 20.849 5.11458 17.3021 8.3868 13.9613Z"
                                fill="#2405F2"
                            />
                            <path
                                d="M17.4882 13.0249C14.7555 12.797 12.3802 13.0275 10.3314 14.7187C6.90288 17.4649 7.56268 21.1625 7.56268 25.6861C7.56268 26.8829 8.53642 27.8748 9.75141 27.8748C22.9439 27.8748 23.469 28.3003 24.2513 26.5679C24.5078 25.9821 24.4375 26.1682 24.4375 20.5636C24.4375 16.112 20.583 13.0249 17.4882 13.0249Z"
                                fill="#2405F2"
                            />
                            <path
                                d="M27.7564 13.0004C26.1833 13.0004 24.9646 12.8552 23.6133 13.9623C26.8611 17.2783 26.3126 20.5832 26.3126 25.6865C26.3126 25.9562 25.8749 25.8753 30.0963 25.8753C31.1463 25.8753 32.0001 25.0247 32.0001 23.9791V17.2185C32.0001 14.8929 30.0963 13.0004 27.7564 13.0004Z"
                                fill="#2405F2"
                            />
                        </svg>

                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] pt-[26px] pb-[12px]"
                        >
                            Customize with ease
                        </p>
                        <p
                            class="max-w-[324.079px] font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                        >
                            Lorem ipsum dolor sit amet, consectetur adipiscing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua ut enim.
                        </p>
                    </div>
                </div>
            </div>

            <!-- Logos -->
            <div class="flex flex-row gap-[89px] items-center pb-[152px]">
                <div>
                    <p
                        class="font-sans text-[38px] font-semibold leading-[56px] pt-[48px]"
                    >
                        100.000+
                    </p>
                    <p class="font-sans text-[16px] font-normal leading-[28px]">
                        Finsweet Users
                    </p>
                </div>
                <div
                    class="flex pt-[76px] sm:flex-col sm:items-start sm:gap-[20px] md:flex-col md:items-start md:gap-[20px] lg:flex-col lg:items-start xl:flex-row"
                >
                    <!-- logo 1 -->
                    <img
                        src="/src/lib/assets/Logo 1.png"
                        alt=""
                        class="pr-[59.09px]"
                    />
                    <!-- logo 2 -->
                    <img src="/src/lib/assets/Logo 2.png" alt="" />

                    <!-- logo 3 -->
                    <img
                        src="/src/lib/assets/Logo 3.png"
                        alt=""
                        class="pr-[59.09px]"
                    />
                    <!-- logo 4 -->
                    <img
                        src="/src/lib/assets/Logo 4.png"
                        alt=""
                        class="pr-[59.09px]"
                    />
                    <!-- logo 5 -->
                    <img src="/src/lib/assets/Logo 5.png" alt="" />
                </div>
            </div>
        </div>

        <!-- Meet our team -->
        <div class="bg-[#F4F6FC] flex flex-col items-center pb-[128px]">
            <p
                class="font-sans text-[48px] font-semibold leading-[64px] pb-[48px] pt-[128px]"
            >
                Meet our team
            </p>
            <div class="flex flex-row">
                <!-- Team Images -->
                <div
                    class="flex gap-[32px] sm:flex-col md:flex-col lg:flex-row xl:flex-row"
                >
                    <div
                        class="max-w-[296px] bg-white px-[64px] pt-[48px] pb-[32px]"
                    >
                        <div class="flex flex-col items-center relative">
                            <img
                                src="/src/lib/assets/man-in-black-suit-holding-a-calling-card-3785104.png"
                                alt=""
                            />
                            <!-- gradient -->
                            <svg
                                class="absolute"
                                xmlns="http://www.w3.org/2000/svg"
                                width="168"
                                height="168"
                                viewBox="0 0 168 168"
                                fill="none"
                            >
                                <path
                                    d="M168 84C168 130.392 130.392 168 84 168C37.6081 168 0 130.392 0 84C0 37.6081 37.6081 0 84 0C130.392 0 168 37.6081 168 84Z"
                                    fill="url(#paint0_linear_126_164)"
                                />
                                <defs>
                                    <linearGradient
                                        id="paint0_linear_126_164"
                                        x1="66"
                                        y1="199.5"
                                        x2="41.5"
                                        y2="80.5"
                                        gradientUnits="userSpaceOnUse"
                                    >
                                        <stop stop-color="#5239FA" />
                                        <stop
                                            offset="1"
                                            stop-color="white"
                                            stop-opacity="0"
                                        />
                                    </linearGradient>
                                </defs>
                            </svg>

                            <!-- <div class="h-72 bg-gradient-to-t from-purple-800 to-blue[#5239FA ] w-[168px] h-[168px] rounded-full"><p>contact btn</p></div> -->
                            <div
                                class=" flex gap-[11.25px] absolute top-[130px]"
                            >
                                <!-- fb -->
                                <svg
                                    width="13"
                                    height="13"
                                    viewBox="0 0 13 13"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <g clip-path="url(#clip0_126_166)">
                                        <path
                                            d="M13 6.5C13 2.91015 10.0899 0 6.5 0C2.91015 0 0 2.91015 0 6.5C0 9.74429 2.37694 12.4334 5.48438 12.921V8.37891H3.83398V6.5H5.48438V5.06797C5.48438 3.43891 6.45481 2.53906 7.93952 2.53906C8.65046 2.53906 9.39453 2.66602 9.39453 2.66602V4.26562H8.57492C7.7675 4.26562 7.51563 4.76671 7.51563 5.28125V6.5H9.31836L9.03018 8.37891H7.51563V12.921C10.6231 12.4334 13 9.74429 13 6.5Z"
                                            fill="white"
                                        />
                                    </g>
                                    <defs>
                                        <clipPath id="clip0_126_166">
                                            <rect
                                                width="13"
                                                height="13"
                                                fill="white"
                                            />
                                        </clipPath>
                                    </defs>
                                </svg>
                                <!-- Twitter -->
                                <svg
                                    width="14"
                                    height="13"
                                    viewBox="0 0 14 13"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <g clip-path="url(#clip0_126_168)">
                                        <path
                                            d="M4.33967 11.7816C9.24412 11.7816 11.9274 7.71736 11.9274 4.1939C11.9274 4.07965 11.9249 3.96285 11.9198 3.84859C12.4418 3.47111 12.8922 3.00353 13.25 2.46785C12.7639 2.68414 12.2477 2.8254 11.7192 2.8868C12.2757 2.55322 12.6924 2.02919 12.892 1.41185C12.3685 1.72212 11.7959 1.94098 11.1989 2.05906C10.7967 1.63166 10.2649 1.34867 9.68566 1.25384C9.10646 1.15901 8.51215 1.25763 7.99461 1.53445C7.47707 1.81127 7.06514 2.25086 6.8225 2.78527C6.57986 3.31969 6.52002 3.91915 6.65225 4.49098C5.59218 4.43778 4.55513 4.1624 3.60832 3.6827C2.66151 3.203 1.82608 2.52968 1.15619 1.70639C0.815716 2.2934 0.711531 2.98804 0.864808 3.64911C1.01809 4.31019 1.41733 4.8881 1.98139 5.26539C1.55792 5.25195 1.14374 5.13793 0.773047 4.93277V4.96578C0.772668 5.58181 0.985636 6.17896 1.37575 6.65573C1.76587 7.1325 2.30905 7.45945 2.91297 7.58101C2.5207 7.68834 2.10899 7.70398 1.70971 7.62672C1.88012 8.15651 2.21169 8.61988 2.65813 8.95216C3.10457 9.28444 3.64361 9.46905 4.20002 9.48023C3.2554 10.2222 2.08851 10.6247 0.887305 10.6228C0.674281 10.6225 0.461466 10.6094 0.25 10.5837C1.4703 11.3666 2.88983 11.7824 4.33967 11.7816Z"
                                            fill="white"
                                        />
                                    </g>
                                    <defs>
                                        <clipPath id="clip0_126_168">
                                            <rect
                                                width="13"
                                                height="13"
                                                fill="white"
                                                transform="translate(0.25)"
                                            />
                                        </clipPath>
                                    </defs>
                                </svg>
                                <!-- linkedIn -->
                                <svg
                                    width="14"
                                    height="13"
                                    viewBox="0 0 14 13"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <g clip-path="url(#clip0_126_170)">
                                        <path
                                            d="M12.5377 0H1.45977C0.929102 0 0.5 0.418945 0.5 0.936914V12.0605C0.5 12.5785 0.929102 13 1.45977 13H12.5377C13.0684 13 13.5 12.5785 13.5 12.0631V0.936914C13.5 0.418945 13.0684 0 12.5377 0ZM4.35684 11.0779H2.42715V4.87246H4.35684V11.0779ZM3.39199 4.02695C2.77246 4.02695 2.27227 3.52676 2.27227 2.90977C2.27227 2.29277 2.77246 1.79258 3.39199 1.79258C4.00898 1.79258 4.50918 2.29277 4.50918 2.90977C4.50918 3.52422 4.00898 4.02695 3.39199 4.02695ZM11.5779 11.0779H9.65078V8.06152C9.65078 7.34297 9.63809 6.41621 8.64785 6.41621C7.64492 6.41621 7.49258 7.20078 7.49258 8.01074V11.0779H5.56797V4.87246H7.41641V5.72051H7.4418C7.69824 5.23301 8.32793 4.71758 9.26484 4.71758C11.2174 4.71758 11.5779 6.00234 11.5779 7.67305V11.0779Z"
                                            fill="white"
                                        />
                                    </g>
                                    <defs>
                                        <clipPath id="clip0_126_170">
                                            <rect
                                                width="13"
                                                height="13"
                                                fill="white"
                                                transform="translate(0.5)"
                                            />
                                        </clipPath>
                                    </defs>
                                </svg>
                            </div>

                            <p
                                class="pt-[30px] font-sans text-[24px] font-medium leading-[36px]"
                            >
                                John Smith
                            </p>
                            <p
                                class="pt-[30px] font-sans text-[16px] font-normal leading-[28px]"
                            >
                                CEO
                            </p>
                        </div>
                    </div>
                    <!-- img 2 -->
                    <div
                        class="max-w-[296px] bg-white px-[64px] pt-[48px] pb-[32px]"
                    >
                        <div class="flex flex-col items-center">
                            <img
                                src="/src/lib/assets/serious-man-3760373.png"
                                alt=""
                            />
                            <p
                                class="pt-[30px] font-sans text-[24px] font-medium leading-[36px]"
                            >
                                Simon Adams
                            </p>
                            <p
                                class="pt-[30px] font-sans text-[16px] font-normal leading-[28px]"
                            >
                                CTO
                            </p>
                        </div>
                    </div>
                    <!-- img 3 -->
                    <div
                        class="max-w-[296px] bg-white px-[64px] pt-[48px] pb-[32px]"
                    >
                        <div class="flex flex-col items-center">
                            <img
                                src="/src/lib/assets/man-in-white-shirt-wearing-blue-bucket-hat-6626874.png"
                                alt=""
                            />
                            <p
                                class="pt-[30px] font-sans text-[24px] font-medium leading-[36px]"
                            >
                                Paul Jones
                            </p>
                            <p
                                class="pt-[30px] font-sans text-[16px] font-normal leading-[28px]"
                            >
                                Design Lead
                            </p>
                        </div>
                    </div>
                    <!-- img 4 -->
                    <div
                        class="max-w-[296px] bg-white px-[64px] pt-[48px] pb-[32px]"
                    >
                        <div class="flex flex-col items-center">
                            <img
                                src="/src/lib/assets/transgender-model-touching-forehead-in-neon-light-7613875.png"
                                alt=""
                            />
                            <p
                                class="pt-[30px] font-sans text-[24px] font-medium leading-[36px]"
                            >
                                Sara Hardin
                            </p>
                            <p
                                class="pt-[30px] font-sans text-[16px] font-normal leading-[28px]"
                            >
                                Project Manager
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</main>
<Footer />
