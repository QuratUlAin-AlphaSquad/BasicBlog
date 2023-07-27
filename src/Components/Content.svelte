<script>
    import ViewProjects from "../lib/assets/ViewProjects.png";
    import HoverOverlay from "../lib/assets/Hover Overlay.png";
    import Card from "../lib/assets/Card.png";
    import Illustration from "$lib/assets/Illustration.png";
    import pointer1 from "$lib/assets/pointer 1.png";
    import pointer2 from "$lib/assets/pointer 2.png";
    import pointer3 from "$lib/assets/pointer 3.png";
    import pointer4 from "$lib/assets/pointer 4.png";
    import JennyWilson from "$lib/assets/Jenny.png";
    import womanWriting from "$lib/assets/woman-writing-on-paper.png";
    import businessman from "$lib/assets/arabic-businessman-standing-on-street-and-using-laptop.png";
    import macbook from "$lib/assets/woman-in-white-sleeveless-shirt-using-macbook-air-on-brown-wooden-table-3766189.png";
    import applemonitors from "$lib/assets/apple-monitors-326518.png";

    // import { onMount } from "svelte";
    // import { page } from "$app/stores";

    // let posts = [];
    // onMount(async () => {
    //     const response = await fetch(
    //         "https://jsonplaceholder.typicode.com/photos"
    //     );
    //     const dt = await response.json();
    //     posts = dt.slice(0, 6);

    //     console.log(posts);
    // });

    // const apiId = $page.params.apiId;
    // let x = 7;

    // onMount(async () => {
    //     const dt = document.getElementById('cards');
    // cards = dt.slice(0, 6);
    // });

    let cards = [
        {
            heading: "Uses Client First",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="32" height="28" viewBox="0 0 32 28" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M16 10.8749C19.003 10.8749 21.4374 8.44047 21.4374 5.43745C21.4374 2.43443 19.003 0 16 0C12.9969 0 10.5625 2.43443 10.5625 5.43745C10.5625 8.44047 12.9969 10.8749 16 10.8749Z" fill="#2405F2"/>
<path d="M27 10.8749C28.8984 10.8749 30.4374 9.33593 30.4374 7.43747C30.4374 5.53901 28.8984 4 27 4C25.1015 4 23.5625 5.53901 23.5625 7.43747C23.5625 9.33593 25.1015 10.8749 27 10.8749Z" fill="#2405F2"/>
<path d="M4.99997 10.8749C6.89843 10.8749 8.43744 9.33587 8.43744 7.43741C8.43744 5.53895 6.89843 3.99994 4.99997 3.99994C3.10151 3.99994 1.5625 5.53895 1.5625 7.43741C1.5625 9.33587 3.10151 10.8749 4.99997 10.8749Z" fill="#2405F2"/>
<path d="M8.3868 13.9614C7.03369 12.8528 5.80826 12.9995 4.24371 12.9995C1.90373 12.9995 0 14.892 0 17.2176V24.0432C0 25.0532 0.824368 25.8744 1.83811 25.8744C6.21469 25.8744 5.68745 25.9536 5.68745 25.6857C5.68745 20.8491 5.11458 17.3022 8.3868 13.9614Z" fill="#2405F2"/>
<path d="M17.4882 13.0249C14.7555 12.797 12.3802 13.0275 10.3314 14.7187C6.90288 17.4649 7.56268 21.1625 7.56268 25.6861C7.56268 26.8829 8.53642 27.8748 9.75141 27.8748C22.9439 27.8748 23.469 28.3003 24.2513 26.5679C24.5078 25.9821 24.4375 26.1682 24.4375 20.5636C24.4375 16.112 20.583 13.0249 17.4882 13.0249Z" fill="#2405F2"/>
<path d="M27.7564 13.0004C26.1833 13.0004 24.9646 12.8552 23.6133 13.9623C26.8611 17.2783 26.3126 20.5832 26.3126 25.6865C26.3126 25.9562 25.8749 25.8753 30.0963 25.8753C31.1463 25.8753 32.0001 25.0247 32.0001 23.9791V17.2185C32.0001 14.8929 30.0963 13.0004 27.7564 13.0004Z" fill="#2405F2"/>
</svg>

`,
        },

        {
            heading: "Two Free Revision Round",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M16 0C7.21187 0 0 7.21187 0 16C0 24.7881 7.21187 32 16 32C24.7881 32 32 24.7881 32 16C32 7.21187 24.7881 0 16 0ZM14.0637 23.2775L7.05713 16.271L9.7085 13.6196L14.1864 18.0975L23.1759 9.9255L25.6991 12.6996L14.0637 23.2775Z" fill="#2405F2"/>
</svg>


`,
        },
        {
            heading: "Template Customization",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_126_495)">
<path d="M2.64172 9.89299L9.89237 2.64235L8.68379 1.43377C6.68481 -0.565208 3.43213 -0.565208 1.43341 1.43404C0.464898 2.40229 -0.0683594 3.68964 -0.0683594 5.05923C-0.0683594 6.42856 0.464898 7.71617 1.43341 8.68442L2.64172 9.89299Z" fill="#2405F2"/>
<path d="M4.0918 11.3426L6.992 8.44238L11.1478 12.5982L8.24757 15.4984L4.0918 11.3426Z" fill="#2405F2"/>
<path d="M8.44238 6.992L11.3426 4.0918L15.4984 8.24731L12.5982 11.1475L8.44238 6.992Z" fill="#2405F2"/>
<path d="M24.9643 30.764C24.9643 30.7643 24.9643 30.7643 24.964 30.7643L24.4863 31.2423L33.5261 34.8581C33.6494 34.9075 33.7784 34.9315 33.9066 34.9315C34.1736 34.9315 34.4358 34.8271 34.6318 34.6311C34.9218 34.3411 35.011 33.9061 34.8588 33.5251L31.243 24.4854L24.9643 30.764Z" fill="#2405F2"/>
<path d="M19.3652 26.615L22.2654 23.7148L25.6888 27.1384L22.7886 30.0386L19.3652 26.615Z" fill="#2405F2"/>
<path d="M23.7148 22.2657L26.615 19.3652L30.0386 22.7888L27.1384 25.689L23.7148 22.2657Z" fill="#2405F2"/>
<path d="M8.80609 27.5075C8.40555 27.9078 8.40555 28.5572 8.80609 28.9575L11.4646 31.616L8.44934 34.6313C8.04907 35.0318 7.39965 35.0318 6.99937 34.6313L0.232049 27.864C-0.168495 27.4637 -0.168495 26.8143 0.232049 26.414L26.414 0.232049C26.8143 -0.168495 27.4637 -0.168495 27.864 0.232049L34.6313 6.99911C34.8316 7.19938 34.9317 7.46187 34.9317 7.72436C34.9317 7.98658 34.8316 8.24907 34.6313 8.44934L31.616 11.4646L27.9908 7.83918C27.5903 7.43864 26.9411 7.43864 26.5406 7.83918C26.1403 8.23973 26.1403 8.88887 26.5406 9.28942L30.1658 12.9146L27.8757 15.2049L25.2172 12.5461C24.8169 12.1458 24.1675 12.1458 23.7669 12.5461C23.3667 12.9467 23.3667 13.5958 23.7669 13.9963L26.4255 16.6549L24.1354 18.9452L20.5103 15.3197C20.1097 14.9195 19.4606 14.9195 19.06 15.3197C18.6597 15.7203 18.6597 16.3694 19.06 16.77L22.6852 20.3952L20.3952 22.6855L17.7366 20.0269C17.3361 19.6264 16.6869 19.6264 16.2864 20.0269C15.8861 20.4272 15.8861 21.0764 16.2864 21.4769L18.9449 24.1354L16.6549 26.4258L13.0297 22.8003C12.6292 22.4 11.98 22.4 11.5795 22.8003C11.1792 23.2008 11.1792 23.85 11.5795 24.2505L15.2047 27.8757L12.9146 30.166L10.2561 27.5075C9.85579 27.107 9.20637 27.107 8.80609 27.5075Z" fill="#2405F2"/>
</g>
<defs>
<clipPath id="clip0_126_495">
<rect width="35" height="35" fill="white"/>
</clipPath>
</defs>
</svg>



`,
        },
        {
            heading: "24/7 Support",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_126_549)">
<path d="M34.9994 23.686C34.9994 19.3427 32.5078 15.4665 28.7761 13.5811C28.6602 21.9086 21.9086 28.6602 13.5811 28.7761C15.4665 32.5078 19.3427 34.9994 23.686 34.9994C25.7223 34.9994 27.7026 34.4571 29.4426 33.4266L34.95 34.95L33.4266 29.4426C34.4571 27.7026 34.9994 25.7223 34.9994 23.686Z" fill="#2405F2"/>
<path d="M26.7285 13.3643C26.7285 5.99506 20.7335 0 13.3643 0C5.99506 0 0 5.99506 0 13.3643C0 15.7659 0.639267 18.1043 1.85318 20.1572L0.0491333 26.6791L6.57131 24.8753C8.62423 26.0892 10.9626 26.7285 13.3643 26.7285C20.7335 26.7285 26.7285 20.7335 26.7285 13.3643ZM11.3135 10.2539H9.2627C9.2627 7.99217 11.1025 6.15234 13.3643 6.15234C15.626 6.15234 17.4658 7.99217 17.4658 10.2539C17.4658 11.4019 16.9798 12.5052 16.132 13.2807L14.3896 14.8754V16.4746H12.3389V13.9723L14.7475 11.7677C15.1779 11.3738 15.415 10.8363 15.415 10.2539C15.415 9.12304 14.4951 8.20312 13.3643 8.20312C12.2334 8.20312 11.3135 9.12304 11.3135 10.2539ZM12.3389 18.5254H14.3896V20.5762H12.3389V18.5254Z" fill="#2405F2"/>
</g>
<defs>
<clipPath id="clip0_126_549">
<rect width="35" height="35" fill="white"/>
</clipPath>
</defs>
</svg>



`,
        },
        {
            heading: "Quick Delivery",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="35" height="35" viewBox="0 0 35 35" fill="none" xmlns="http://www.w3.org/2000/svg">
<g clip-path="url(#clip0_126_523)">
<path d="M29.3038 9.94438L31.656 7.59354C32.2263 7.02479 32.2263 6.10167 31.656 5.53146C31.0858 4.96125 30.1642 4.96125 29.594 5.53146L27.2417 7.88229C24.9463 5.985 22.0865 4.74542 18.9583 4.44938V2.91667H21.875C22.6815 2.91667 23.3333 2.26333 23.3333 1.45833C23.3333 0.653333 22.6815 0 21.875 0H13.125C12.3185 0 11.6667 0.653333 11.6667 1.45833C11.6667 2.26333 12.3185 2.91667 13.125 2.91667H16.0417V4.44938C8.28042 5.18583 2.1875 11.7367 2.1875 19.6875C2.1875 28.1313 9.05625 35 17.5 35C25.9438 35 32.8125 28.1313 32.8125 19.6875C32.8125 15.9892 31.4942 12.5942 29.3038 9.94438ZM18.9583 19.6875C18.9583 20.494 18.305 21.1458 17.5 21.1458C16.695 21.1458 16.0417 20.494 16.0417 19.6875V11.6667C16.0417 10.8602 16.695 10.2083 17.5 10.2083C18.305 10.2083 18.9583 10.8602 18.9583 11.6667V19.6875Z" fill="#2405F2"/>
</g>
<defs>
<clipPath id="clip0_126_523">
<rect width="35" height="35" fill="white"/>
</clipPath>
</defs>
</svg>



`,
        },
        {
            heading: "Hands-on approach",
            para: "Euismod faucibus turpis eu gravida mi. Pellentesque et velit aliquam sed faucib turpis eu gravida mi. Pellentesque et velit aliquam sed mi. ",
            svg: `<svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M25.866 5.80537C25.866 5.0077 25.5547 4.25677 24.9905 3.69259L22.1734 0.8755C21.6171 0.319082 20.8273 0 20.0413 0H19.8701V5.97656H25.8661L25.866 5.80537Z" fill="#2405F2"/>
<path d="M18.1911 20.5552C18.3818 19.9764 18.7145 19.4375 19.1483 19.0008L25.8927 12.2836V7.96875H18.8934C18.3429 7.96875 17.9297 7.52323 17.9297 6.97266V0H2.98828C1.34048 0 0 1.34048 0 2.98828V31.0117C0 32.6595 1.34048 34 2.98828 34H22.8778C24.5256 34 25.8927 32.6595 25.8927 31.0117V23.5775L24.798 24.6455C24.3545 25.0852 23.8351 25.4052 23.2494 25.6008L20.0822 26.6582L19.5997 26.6845C18.802 26.6845 18.0472 26.2963 17.5783 25.6466C17.1134 24.9997 16.9869 24.1612 17.2398 23.4034L18.1911 20.5552ZM4.98047 17.9297H14.9091C15.4596 17.9297 15.9052 18.3752 15.9052 18.9258C15.9052 19.4764 15.4596 19.9219 14.9091 19.9219H4.98047C4.42989 19.9219 3.98438 19.4764 3.98438 18.9258C3.98438 18.3752 4.42989 17.9297 4.98047 17.9297ZM3.98438 14.9414C3.98438 14.3908 4.42989 13.9453 4.98047 13.9453H14.9091C15.4596 13.9453 15.9052 14.3908 15.9052 14.9414C15.9052 15.492 15.4596 15.9375 14.9091 15.9375H4.98047C4.42989 15.9375 3.98438 15.492 3.98438 14.9414ZM3.98438 22.9102C3.98438 22.3596 4.42989 21.9141 4.98047 21.9141H14.9091C15.4596 21.9141 15.9052 22.3596 15.9052 22.9102C15.9052 23.4607 15.4596 23.9062 14.9091 23.9062H4.98047C4.42989 23.9062 3.98438 23.4607 3.98438 22.9102ZM18.8934 27.8906C19.444 27.8906 19.8895 28.3361 19.8895 28.8867C19.8895 29.4373 19.4441 29.8828 18.8934 29.8828H12.9169C12.3663 29.8828 11.9208 29.4373 11.9208 28.8867C11.9208 28.3361 12.3663 27.8906 12.9169 27.8906H18.8934ZM4.98047 11.9531C4.42989 11.9531 3.98438 11.5076 3.98438 10.957C3.98438 10.4065 4.42989 9.96094 4.98047 9.96094H18.8934C19.444 9.96094 19.8895 10.4065 19.8895 10.957C19.8895 11.5076 19.444 11.9531 18.8934 11.9531H4.98047Z" fill="#2405F2"/>
<path d="M19.9956 21.4365L19.129 24.0364C18.9991 24.4259 19.3697 24.7964 19.7592 24.6663L22.3575 23.7985L19.9956 21.4365Z" fill="#2405F2"/>
<path d="M27.7321 13.2354L21.1719 19.7956L24.0011 22.6248C25.4838 21.1418 28.3689 18.2564 30.561 16.0643L27.7321 13.2354Z" fill="#2405F2"/>
<path d="M33.4149 10.3777C33.0648 10.0256 32.5492 9.82422 32.0025 9.82422C31.4557 9.82422 30.9402 10.0256 30.5881 10.3787L29.1406 11.8262L31.9694 14.6549C32.7618 13.8624 33.3095 13.3147 33.417 13.2074C34.1951 12.4281 34.195 11.1588 33.4149 10.3777Z" fill="#2405F2"/>
</svg>


`,
        },
    ];

    // //////////////// Test Login btn
</script>

<div class="max-w-[1600px] m-auto">
    <main class="">
        <!-- How we work -->

        <div
            class="bg-[#F4F6FC] flex flex-row pb-[129px] lg:items-center sm:flex-col sm:justify-left md:flex-col md:justify-left"
        >
            <div class="">
                <div
                    class="flex gap-[142px] justify-center sm:flex-col sm:justify-start md:flex-col lg:flex-row"
                >
                    <div
                        class="pt-[128px] lg:pl-[165px] pl-[165px] max-w-[1224px]"
                    >
                        <p
                            class="font-sans text-[48px] font-semibold leading-[64px]"
                        >
                            How we work
                        </p>
                        <p
                            class="font-sans text-[16px] font-normal leading-[28px] max-w-[405px]"
                        >
                            Lorem ipsum dolor sit amet, consectetur adipiscing
                            elit, sed do eiusmod tempor.
                        </p>
                        <div class="flex flex-row items-center gap-[14px]">
                            <div>
                                <p
                                    class="font-sans text-[18px] font-medium leading-[32px] text-[#2405F2]"
                                >
                                    Get in touch with us
                                </p>
                            </div>
                            <div>
                                <svg
                                    width="25"
                                    height="12"
                                    viewBox="0 0 25 12"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <path
                                        d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                        fill="#2405F2"
                                    />
                                </svg>
                            </div>
                        </div>
                    </div>

                    <!-- 4 stratgies Div -->
                    <div
                        class="pt-[128px] flex flex-col gap-[48px] sm:flex-col"
                    >
                        <div>
                            <!-- Stategy 1  -->
                            <div
                                class="flex flex-row items-center justify-center"
                            >
                                <div>
                                    <img src={pointer1} alt="01" />

                                    <p
                                        class="font-sans text-[32px] font-medium leading-[48px]"
                                    >
                                        Strategy
                                    </p>
                                    <p
                                        class="font-sans text-[16px] font-normal leading-[28px] max-w-[303px]"
                                    >
                                        Euismod faucibus turpis eu gravida mi.
                                        Pellentesque et velit aliquam .
                                    </p>
                                </div>
                                <!-- Stategy 2-->
                                <div>
                                    <img src={pointer2} alt="02" />

                                    <p
                                        class="font-sans text-[32px] font-medium leading-[48px]"
                                    >
                                        Wireframing
                                    </p>
                                    <p
                                        class="font-sans text-[16px] font-normal leading-[28px] max-w-[303px]"
                                    >
                                        Euismod faucibus turpis eu gravida mi.
                                        Pellentesque et velit aliquam .
                                    </p>
                                </div>
                            </div>
                        </div>
                        <!-- Stratgey 3 -->
                        <div class="flex flex-row items-center justify-center">
                            <div>
                                <img src={pointer3} alt="03" />

                                <p
                                    class="font-sans text-[32px] font-medium leading-[48px]"
                                >
                                    Design
                                </p>
                                <p
                                    class="font-sans text-[16px] font-normal leading-[28px] max-w-[303px]"
                                >
                                    Euismod faucibus turpis eu gravida mi.
                                    Pellentesque et velit aliquam .
                                </p>
                            </div>
                            <!-- Stratgey 4 -->
                            <div>
                                <img src={pointer4} alt="04" />
                                <p
                                    class="font-sans text-[32px] font-medium leading-[48px]"
                                >
                                    Design
                                </p>
                                <p
                                    class="font-sans text-[16px] font-normal leading-[28px] max-w-[303px]"
                                >
                                    Euismod faucibus turpis eu gravida mi.
                                    Pellentesque et velit aliquam .
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- View our projects -->
        <div class="max-w-[1280px] m-auto pt-[128px] flex flex-col pb-[128px]">
            <!-- inner Div -->
            <div>
                <div
                    class="flex sm:flex-col lg:flex-row items-center justify-between"
                >
                    <div
                        class="font-sans text-[48px] font-semibold leading-[64px]"
                    >
                        <p>View our projects</p>
                    </div>
                    <div class="flex flex-row items-center gap-[16px]">
                        <a
                            href="/"
                            class="font-sans text-[16px] font-medium leading-[28px]"
                            >View More</a
                        >
                        <svg
                            width="25"
                            height="12"
                            viewBox="0 0 25 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>
                <!-- View our projects Imaged -->
                <div
                    class="flex lg:flex-row gap-[31px] sm:flex-col sm:items-center pt-[64px]"
                >
                    <div>
                        <img
                            src={ViewProjects}
                            alt=""
                            class="sm:max-w-[405px] md:max-w-[405px] lg:max-w-[843px]"
                        />
                    </div>
                    <div class="flex flex-col items-center gap-[32px]">
                        <img src={HoverOverlay} alt="" />
                        <img src={Card} alt="" />
                    </div>
                </div>
            </div>
        </div>
        <!-- Features -->
        <div
            class="flex flex-col items-center bg-[#F4F6FC] pb-[128px] gap-[24px]"
        >
            <p
                class="font-sans text-[16px] font-medium leading-[28px] pt-[128px]"
            >
                Features
            </p>
            <p
                class="font-sans text-[48px] font-semibold leading-[64px] max-w-[630px] text-center pb-[47px]"
            >
                Design that solves problems, one product at a time
            </p>
            <!-- Cards -->
            <div class="grid grid-cols-3 gap-x-[32px] gap-y-[24px]">
                {#each cards as card}
                    <div id="cards">
                        <div
                            class="bg-white max-w-[405px] xs:pb-[28px] xs:pt-[38px]   md:pb-[48px] md:pt-[58px] flex flex-row"
                        >
                            <div>
                                {@html card.svg}
                                <p
                                    class="pt-[22.08px] pb-[12px] font-sans text-[24px] font-medium leading-[36px] "
                                >
                                    {card.heading}
                                </p>
                                <p
                                    class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                                >
                                    {card.para}
                                </p>
                            </div>
                        </div>
                    </div>
                {/each}
            </div>
        </div>

        <!-- What our clients say about us -->
        <div
            class="flex flex-row justify-center gap-[110px] pl-[160px] pr-[160px] pt-[128px] pb-[128px] bg-[#F4F6FC]/[0.5]"
        >
            <!-- Div1 -->
            <div>
                <p
                    class="font-sans text-[38px] font-semibold leading-[56px] max-w-[327px]"
                >
                    What our clients say about us
                </p>
                <p
                    class="font-sans text-[16px] font-normal leading-[28px] max-w-[327px] opacity-[0.699999988079071]"
                >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit sed.
                </p>
            </div>
            <!-- Div 2 -->
            <div class="flex flex-col gap-[48px]">
                <p
                    class="font-sans text-[32px] font-medium leading-[48px] max-w-[843px]"
                >
                    "The best agency we’ve worked with so far. They understand
                    our product and are able to add new features with a great
                    focus."
                </p>
                <div class="flex flex-row justify-between">
                    <div class="flex flex-row gap-[14px] items-center">
                        <div>
                            <img src={JennyWilson} alt="JennyWilson" />
                        </div>
                        <div>
                            <p
                                class="font-sans text-[18px] font-medium leading-[32px]"
                            >
                                Jenny Wilson
                            </p>
                            <p
                                class="font-sans text-[12px] font-medium leading-[28px]"
                            >
                                Vice President
                            </p>
                        </div>
                    </div>
                    <div class="flex flex-row">
                        <svg
                            width="49"
                            height="48"
                            viewBox="0 0 49 48"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <ellipse
                                cx="24.1"
                                cy="24"
                                rx="24.0997"
                                ry="24"
                                transform="rotate(-180 24.1 24)"
                                fill="white"
                            />
                            <path
                                opacity="0.6"
                                d="M28.5864 13L30.0005 16.2195L20.97 23.9106L30.0005 31.7805L28.5864 35L17.0005 24.626L17.0005 22.8374L28.5864 13Z"
                                fill="#282938"
                            />
                        </svg>

                        <svg
                            width="49"
                            height="48"
                            viewBox="0 0 49 48"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <ellipse
                                cx="24.1002"
                                cy="24"
                                rx="24.0997"
                                ry="24"
                                fill="#5239FA"
                            />
                            <path
                                d="M18.4146 35L17.0005 31.7805L26.031 24.0894L17.0005 16.2195L18.4146 13L30.0005 23.374V25.1626L18.4146 35Z"
                                fill="white"
                            />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
        <!-- Frequently asked questions -->
        <div
            class="flex gap-[136px] pt-[128px] pb-[128px] justify-center sm:flex-col sm:items-center md:flex-col md:items-center lg:flex-col lg:items-center xl:flex-row xl:items-start"
        >
            <!-- Heading -->
            <div>
                <p class="font-sans text-[38px] font-semibold leading-[56px]">
                    Frequently asked questions
                </p>
                <p
                    class="font-sans text-[18px] font-medium leading-[32px] text-[#2405F2]/[0.8700000047683716]"
                >
                    Contact us for more info
                </p>
            </div>
            <!-- FAQs -->
            <div class="sm:max-w-[646px] md:max-w-[1600px] lg:max-w-[1600px]">
                <div class="flex flex-row justify-between">
                    <div>
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] text-[#2405F2]"
                        >
                            01
                        </p>
                    </div>
                    <div class="pl-[59px]">
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px]"
                        >
                            How much time does it take?
                        </p>
                        <p
                            class="font-sans text-[18px] font-medium leading-[32px] max-w-[624px] pb-[48px] pr-[89.68px]"
                        >
                            Lorem ipsum dolor sit amet, consectetur adipiscing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua.
                        </p>
                    </div>
                    <svg
                        width="14"
                        height="14"
                        viewBox="0 0 14 14"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            opacity="0.7"
                            d="M12.1495 13.1605L7.12057 8.1316L1.96717 13.285L0.711315 12.0292L5.86472 6.87575L0.835794 1.84682L1.84269 0.839932L6.87161 5.86886L12.025 0.715453L13.2809 1.9713L8.12746 7.12471L13.1564 12.1536L12.1495 13.1605Z"
                            fill="#282938"
                        />
                    </svg>
                </div>
                <div class="max-w-[843px] bg-[#ECECF1] min-h-[2px]" />

                <div class="flex flex-row items-center pt-[32px] pb-[32px]">
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] text-[#2405F2]"
                    >
                        02
                    </p>
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pl-[53px] pr-[241px]"
                    >
                        What is your class naming convention?
                    </p>
                    <svg
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            opacity="0.7"
                            d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z"
                            fill="#282938"
                        />
                    </svg>
                </div>
                <div class="max-w-[843px] bg-[#ECECF1] min-h-[2px]" />

                <!-- <div > -->
                <div class="flex flex-row items- pt-[32px] pb-[32px]">
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] text-[#2405F2]"
                    >
                        03
                    </p>
                    <p
                        class="font-sans text-[24px] font-medium leading-[36px] pl-[55px] pr-[365px]"
                    >
                        How do you communicate?
                    </p>
                    <svg
                        width="16"
                        height="16"
                        viewBox="0 0 16 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            opacity="0.7"
                            d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z"
                            fill="#282938"
                        />
                    </svg>
                </div>
                <!-- </div> -->
                <div class="max-w-[843px] bg-[#ECECF1] min-h-[2px]" />

                <div>
                    <div class="flex flex-row items-center pt-[32px] pb-[32px]">
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] text-[#2405F2]"
                        >
                            04
                        </p>
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] pl-[55px] pr-[203px]"
                        >
                            I have a bigger project. Can you handle it?
                        </p>
                        <svg
                            width="16"
                            height="16"
                            viewBox="0 0 16 16"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                opacity="0.7"
                                d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>
                <div class="max-w-[843px] bg-[#ECECF1] min-h-[2px]" />

                <div>
                    <div class="flex flex-row items-center pt-[32px]">
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] text-[#2405F2]"
                        >
                            05
                        </p>
                        <p
                            class="font-sans text-[24px] font-medium leading-[36px] pl-[55px] pr-[241px]"
                        >
                            What is your class naming convention?
                        </p>
                        <svg
                            width="16"
                            height="16"
                            viewBox="0 0 16 16"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                opacity="0.7"
                                d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
        <!-- Building stellar websites for early startups IMAGE -->

        <div
            class="flex flex-row justify-center m-auto w-[1280px] bg-[#1C1E53]/[0.50] sm:flex-col sm:w-[640px] md:flex-col md:w-[656px] lg:flex-col lg:w-[656px] xl:flex-row xl:w-[656px]"
        >
            <div class="relative">
                <!-- Img -->
                <!-- <div class="bg-cover" style="backgound-image:url('/src/lib/assets/woman-writing-on-paper.png')"></div> -->

                <img
                    class="max-w-full lg:max-w-[656px]"
                    src={womanWriting}
                    alt="woman-writing-on-paper"
                />
                <div class="absolute top-[96px] left-[96px]">
                    <p
                        class="font-sans text-[54px] font-semibold leading-[74px] max-w-[464px] text-white"
                    >
                        Building stellar websites for early startups
                    </p>
                    <p
                        class="font-sans text-[16px] font-medium leading-[28px] max-w-[464px] text-white"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor incididunt ut labore et dolore
                        magna aliqua ut enim.
                    </p>
                </div>
            </div>
            <!--  Send an Inquiry-->
            <div
                class="bg-[#1C1E53] flex flex-col justify-center pl-[96px] pr-[96px] gap-[16px]"
            >
                <p
                    class="text-white font-sans text-[32px] font-medium leading-[48px] pb-[16px]"
                >
                    Send inquiry
                </p>
                <p
                    class="text-white font-sans text-[16px] font-medium leading-[28px] pr-[96px] pb-[40px]"
                >
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore.
                </p>
                <input
                    type="text"
                    placeholder="Your Name"
                    class="border-solid bg-[#1C1E53] border-[2px] border-gray-500 rounded py-[18px] pl-[32px] w-[432px]"
                />
                <input
                    type="text"
                    placeholder="Email"
                    class="border-solid bg-[#1C1E53] border-[2px] border-gray-500 rounded py-[18px] pl-[32px] w-[432px]"
                />
                <input
                    type="text"
                    placeholder="Paste your Figma design URL"
                    class="border-solid bg-[#1C1E53] border-[2px] border-gray-500 rounded py-[18px] pl-[32px] w-[432px]"
                />
                <div
                    class="flex flex-col font-sans text-[18px] font-medium leading-[32px] gap-[28px]"
                >
                    <button
                        class="bg-[#FCD980] rounded-[41px] py-[15px] px-[51px] max-w-[432px]"
                        >Send an Inquiry</button
                    >
                    <div
                        class="flex flex-row items-center gap-[16px] text-white pl-[96px]"
                    >
                        <p>Get in touch with us</p>
                        <svg
                            width="25"
                            height="12"
                            viewBox="0 0 25 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                fill="#F4F6FC"
                            />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
        <!-- Our blog -->
        <div
            class="flex flex-col justify-start pt-[128px] max-w-[1280px] m-auto sm:items-center md:items-start"
        >
            <p class="font-sans text-[48px] font-semibold leading-[64px]">
                Our blog
            </p>
            <!-- Cards -->

            <div
                class="flex flex-row gap-[50px] sm:flex-col sm:items-center md:flex-row md:items-center lg:flex-row"
                id="cards"
            >
                <div class="bg-white max-w-[405px] pb-[48px] pt-[58px]">
                    <img src={businessman} alt="" />

                    <p
                        class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        19 Jan 2022
                    </p>
                    <p class="font-sans text-[24px] font-medium leading-[36px]">
                        How one Webflow user grew his single person consultancy
                        from $0-100K in 14 months
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        See how pivoting to Webflow changed one person’s sales
                        strategy and allowed him to attract
                    </p>
                    <div class="flex flex-row items-center gap-[14px]">
                        <a
                            href="/"
                            class="font-sans text-[16px] font-normal leading-[28px]"
                            >Read More</a
                        >
                        <svg
                            width="25"
                            height="12"
                            viewBox="0 0 25 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>

                <div class="bg-white max-w-[405px] pb-[48px] pt-[58px]">
                    <img src={macbook} alt="" />

                    <p
                        class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        19 Jan 2022
                    </p>
                    <p class="font-sans text-[24px] font-medium leading-[36px]">
                        How one Webflow user grew his single person consultancy
                        from $0-100K in 14 months
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        See how pivoting to Webflow changed one person’s sales
                        strategy and allowed him to attract
                    </p>
                    <div class="flex flex-row items-center gap-[14px]">
                        <a
                            href="/"
                            class="font-sans text-[16px] font-normal leading-[28px]"
                            >Read More</a
                        >
                        <svg
                            width="25"
                            height="12"
                            viewBox="0 0 25 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>
                <div class="bg-white max-w-[405px] pb-[48px] pt-[58px]">
                    <img src={applemonitors} alt="" />

                    <p
                        class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        19 Jan 2022
                    </p>
                    <p class="font-sans text-[24px] font-medium leading-[36px]">
                        How one Webflow user grew his single person consultancy
                        from $0-100K in 14 months
                    </p>
                    <p
                        class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
                    >
                        See how pivoting to Webflow changed one person’s sales
                        strategy and allowed him to attract
                    </p>
                    <div class="flex flex-row items-center gap-[14px]">
                        <a
                            href="/"
                            class="font-sans text-[16px] font-normal leading-[28px]"
                            >Read More</a
                        >
                        <svg
                            width="25"
                            height="12"
                            viewBox="0 0 25 12"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z"
                                fill="#282938"
                            />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </main>
</div>
