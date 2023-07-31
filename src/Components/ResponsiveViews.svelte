<script>
    import Illustration from "$lib/assets/Illustration.png";
    import pointer1 from "$lib/assets/pointer 1.png";
    import pointer2 from "$lib/assets/pointer 2.png";
    import pointer3 from "$lib/assets/pointer 3.png";
    import pointer4 from "$lib/assets/pointer 4.png";
    import ViewProjects from "$lib/assets/ViewProjects.png";
    import HoverOverlay from "$lib/assets/Hover Overlay.png";
    import Card from "$lib/assets/Card.png";
    import JennyWilson from "$lib/assets/Jenny.png";
    import Group1 from "$lib/assets/Group 1.png";
    import businessman from "$lib/assets/arabic-businessman-standing-on-street-and-using-laptop.png";
    import macbook from "$lib/assets/woman-in-white-sleeveless-shirt-using-macbook-air-on-brown-wooden-table-3766189.png";
    import applemonitors from "$lib/assets/apple-monitors-326518.png";
    import Footer from "./Footer.svelte";
    import { fade } from "svelte/transition";




    let show = false;

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
</script>

<!-- <button class="bg-gray-600 rounded hover:bg-yellow-800 	">Transition</button> -->

<!-- HEADER -->
<div class="w-full">
    <!-- <div class="flex items-start justify-around"> -->
    <div
        class="min-h-[50px] md:p-8 w-full bg-[#1C1E53]  flex flex-col justify-center items-center md:flex md:flex-col lg:flex-row lg:justify-around md:justify-center md:items-center sm:flex-row sm:justify-center"
    >
        <!-- svg -->
        <div class="relative lg:max-w-[1600px] w-full justify-between flex">
            <div class="flex w-full justify-between">
                <svg
                    width="122"
                    height="25"
                    viewBox="0 0 122 25"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <g clip-path="url(#clip0_201_12)">
                        <path
                            d="M121.784 18.8714V21.8905H119.251C116.549 21.8056 115.105 20.3462 115.105 17.6051V10.7097H113.336V8.06125H115.105V5.09619H118.842V8.03037H121.699V10.6711H118.842V17.2344C118.842 18.1224 119.019 18.8328 120.386 18.8328L121.784 18.8714Z"
                            fill="white"
                        />
                        <path
                            d="M98.4416 15.0029V14.8021C98.4011 13.914 98.5364 13.0267 98.8395 12.191C99.1427 11.3552 99.6078 10.5876 100.208 9.93193C100.809 9.2763 101.532 8.74561 102.338 8.37027C103.144 7.99493 104.016 7.78232 104.904 7.74463C105.082 7.74463 105.267 7.74463 105.445 7.74463C108.974 7.74463 112.07 9.79855 112.07 14.694V15.7364H102.264C102.364 17.9911 103.584 19.2651 105.638 19.2651C107.406 19.2651 108.232 18.493 108.472 17.3656H112.001C111.568 20.3075 109.221 21.9445 105.507 21.9445C101.43 21.9136 98.4416 19.3346 98.4416 15.0029ZM108.395 13.3736C108.263 11.3197 107.229 10.3313 105.43 10.3313C103.63 10.3313 102.596 11.4432 102.341 13.3736H108.395Z"
                            fill="white"
                        />
                        <path
                            d="M83.184 15.0029V14.8021C83.1436 13.9153 83.2783 13.0291 83.5805 12.1944C83.8827 11.3596 84.3464 10.5926 84.9452 9.9372C85.544 9.28177 86.266 8.75078 87.0701 8.37456C87.8742 7.99835 88.7446 7.78429 89.6315 7.74463C89.8091 7.74463 89.9944 7.74463 90.172 7.74463C93.7007 7.74463 96.8048 9.79855 96.8048 14.694V15.7364H87.0062C87.1065 17.9911 88.3266 19.2651 90.3805 19.2651C92.1487 19.2651 92.9749 18.493 93.2143 17.3656H96.743C96.3029 20.3075 93.9555 21.9445 90.2415 21.9445C86.1722 21.9136 83.184 19.3346 83.184 15.0029ZM93.1371 13.3736C93.0058 11.3197 91.9711 10.3313 90.172 10.3313C88.3729 10.3313 87.3691 11.4741 87.0834 13.3659L93.1371 13.3736Z"
                            fill="white"
                        />
                        <path
                            d="M61.7722 8.03027H65.7256L68.1425 17.188L70.7909 8.03027H73.8796L76.2732 17.188L78.8213 8.03027H82.4427L78.1496 21.6356H74.4432L72.1268 13.0956L69.6482 21.6356H65.8955L61.7722 8.03027Z"
                            fill="white"
                        />
                        <path
                            d="M49.2092 17.358H52.738C52.9001 18.5858 53.5101 19.2884 55.1316 19.2884C56.5833 19.2884 57.2551 18.7402 57.2551 17.8059C57.2551 16.8716 56.4829 16.4778 54.5062 16.1998C50.8848 15.6516 49.4872 14.6092 49.4872 11.953C49.4872 9.11918 52.0816 7.71387 54.8923 7.71387C57.9114 7.71387 60.1892 8.81032 60.5135 11.9375H57.0311C57.0089 11.6958 56.939 11.4608 56.8254 11.2462C56.7119 11.0317 56.557 10.8417 56.3696 10.6873C56.1822 10.533 55.9661 10.4173 55.7337 10.3469C55.5013 10.2766 55.2574 10.2529 55.0158 10.2774H54.9C53.68 10.2774 52.9696 10.8488 52.9696 11.6827C52.9696 12.5167 53.6259 12.8796 55.6181 13.1653C59.0001 13.6749 60.8919 14.532 60.8919 17.443C60.8919 20.354 58.753 21.9137 55.1702 21.9137C51.5875 21.9137 49.3096 20.2999 49.2092 17.358Z"
                            fill="white"
                        />
                        <path
                            d="M34.2141 8.03049H37.9513V10.1848C38.3726 9.39406 39.012 8.74088 39.7935 8.30288C40.5751 7.86487 41.466 7.66045 42.3603 7.7139C45.0088 7.7139 46.9314 9.3277 46.9314 13.0109V21.6667H43.2406V13.5514C43.2406 11.7059 42.5225 10.8257 40.8546 10.8257C40.5021 10.795 40.147 10.8342 39.8097 10.9411C39.4724 11.048 39.1595 11.2205 38.889 11.4487C38.6185 11.6768 38.3958 11.9561 38.2335 12.2706C38.0713 12.5851 37.9728 12.9285 37.9436 13.2811C37.9243 13.4453 37.9243 13.6111 37.9436 13.7753V21.6358H34.2141V8.03049Z"
                            fill="white"
                        />
                        <path
                            d="M27.0022 4.60972C26.9887 4.2371 27.086 3.86885 27.2819 3.55157C27.4777 3.2343 27.7633 2.98228 28.1025 2.82742C28.4417 2.67256 28.8192 2.62182 29.1872 2.68162C29.5553 2.74143 29.8973 2.90909 30.17 3.16339C30.4427 3.41768 30.6338 3.74717 30.7191 4.11014C30.8044 4.4731 30.7801 4.85323 30.6493 5.20238C30.5184 5.55153 30.287 5.85401 29.9841 6.07153C29.6813 6.28904 29.3207 6.4118 28.948 6.42428H28.8785C28.6473 6.43891 28.4154 6.40774 28.1961 6.33255C27.9769 6.25736 27.7747 6.13963 27.6011 5.98611C27.4275 5.83258 27.2859 5.6463 27.1845 5.43793C27.083 5.22956 27.0237 5.00321 27.0099 4.77187C27.0035 4.71807 27.0009 4.66388 27.0022 4.60972ZM27.0022 8.03035H30.778V21.6357H27.0177L27.0022 8.03035Z"
                            fill="white"
                        />
                        <path
                            d="M12.7715 3.04224H24.709V6.33932H16.9874V11.2579H23.1029V14.4315H16.9797V21.6357H12.7715V3.04224Z"
                            fill="white"
                        />
                        <path
                            d="M5.56722 9.12683C5.56722 10.2928 5.56722 11.7135 3.96114 12.2927C5.60582 12.8563 5.56722 14.0532 5.56722 15.3041V19.937C5.56722 20.8172 5.92241 21.35 6.55557 21.4813C6.6947 21.5282 6.84127 21.5491 6.98797 21.543H8.53228V24.6316H5.98418C3.2662 24.6316 1.76823 23.0873 1.76823 20.2227V14.7404C1.74895 14.4589 1.62485 14.1949 1.42043 14.0005C1.216 13.8061 0.946116 13.6954 0.664051 13.6903H0V10.98H0.664051C0.951744 10.9762 1.22693 10.8618 1.43252 10.6605C1.63812 10.4592 1.75833 10.1865 1.76823 9.89899V4.33949C1.76823 1.52114 3.23532 0 5.98418 0H8.55544V3.04228H7.01114C6.86426 3.0427 6.71835 3.06615 6.57873 3.11177C5.94557 3.27392 5.59038 3.79899 5.59038 4.65608L5.56722 9.12683Z"
                            fill="white"
                        />
                    </g>
                    <defs>
                        <clipPath id="clip0_201_12">
                            <rect width="122" height="24.7089" fill="white" />
                        </clipPath>
                    </defs>
                </svg>
                <!-- hamburger -->
                <button
                    class="lg:hidden"
                    on:click|preventDefault={() => (show = !show)}
                >
                    {#if show}
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-6 h-6 text-white"
                        >
                            <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                d="M6 18L18 6M6 6l12 12"
                            />
                        </svg>
                    {:else}
                        <svg
                            xmlns="http://www.w3.org/2000/svg"
                            fill="none"
                            viewBox="0 0 24 24"
                            stroke-width="1.5"
                            stroke="currentColor"
                            class="w-6 h-6 text-white flex items-right"
                        >
                            <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
                            />
                        </svg>
                    {/if}
                </button>
            </div>
            <!-- Nav-Items -->
            {#if show}
                <div
                    id="navItems"
                    class="absolute bg-[#1C1E53] lg:flex-row lg:gap-[8px] flex flex-col justify-center items-center lg:hidden  w-full z-1 top-9"
                >
                    <ul class=" lg:flex lg:flex-row gap-[32px] text-[#BBBBCB]">
                        <li class="text-white">Home</li>
                        <a href="/">About us</a>
                        <li>Features</li>
                        <li>Pricing</li>
                        <li>FAQ</li>
                        <li>Blog</li>
                    </ul>
                    <button
                        class="border-solid lg:border-2 border-gray-600 rounded-full px-[28px] py-[8px] lg:px-[48px] lg:py-[16px] lg:w-[185px] text-[#BBBBCB] cursor-pointer transition ease-in-out duration-300"
                        >Contact us</button
                    >
                </div>
            {/if}
        </div>
        <div
            id="navItems"
            class="hidden lg:flex lg:flex-row lg:gap-[48px] flex-col justify-center items-center w-full"
        >
        
            <ul class=" lg:flex lg:flex-row gap-[32px] text-[#BBBBCB]">
                <li class="text-white cursor-pointer">Home</li>
                <a href="/" class="cursor-pointer">About us</a>
                <li class="cursor-pointer">Features</li>
                <li class="cursor-pointer">Pricing</li>
                <li class="cursor-pointer">FAQ</li>
                <li class="cursor-pointer">Blog</li>
            </ul>
            <button
                class=" w-full border-solid lg:border-2 border-gray-600 rounded-full px-[28px] py-[8px] lg:px-[28px] lg:py-[8px] lg:w-[145px] text-[#BBBBCB] hover:bg-[rgb(49,40,17)] transition ease-in-out duration-700"
                >Contact us</button
            >
        </div>
    </div>
    <!-- </div> -->

    <div class="bg-[#1C1E53] text-white xs:py-6 xs:px-4 md:py-32 lg:px-11">
        <div
            class="flex flex-col md:flex-col lg:flex-row justify-center items-center xs:gap-6 md:gap-[60px] w-full"
        >
            <div class="max-w-[582px] flex flex-col xs:gap-6 md:gap-12">
                <div>
                    <p
                        class="xs:text-[18px] md:text-[38px] font-sans lg:text-[54px] font-semibold "
                    >
                        Building stellar websites for early startups
                    </p>
                    <p
                        class="xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor incididunt.
                    </p>
                </div>
                <!-- btn view our work div -->
                <div class="flex xs:flex-col md:flex-row md:gap-10 xs:gap-5">
                    <button transition:fade
                        class="bg-[#FCD980] rounded-full xs:py-2 xs:px-5 md:py-4 md:px-14 text-black hover:bg-[rgb(223,184,87)] transition ease-in-out duration-700 animate-pulse "
                        >View our work</button
                    >
                    <div
                        class="flex flex-row justify-center items-center gap-4 "
                    >
                        <a class="cursor-pointer" href="/">View Pricing</a>
                        <svg class=" cursor-pointer"
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
            <div>
                <img src={Illustration} alt=""/>
            </div>
        </div>
    </div>
</div>
<!-- ////////// Content -->
<div class="bg-[#F4F6FC]">
    <div class="m-auto max-w-[1600px]">
        <div class="bg-[#F4F6FC] xs:py-5 md:py-22 lg:py-32 xs:px-5 ">
            <!-- How we work: Main Div -->
            <div
                class="flex xs:flex-col xs:justify-center xs:items-center lg:flex-row justify-center xs:gap-7 md:gap-26 lg:gap-36"
            >
                <!-- How we work -->
                <div class="flex flex-col justify-center">
                    <p
                        class="xs:text-[24px] font-sans md:text-[48px] font-semibold leading-[64px]"
                    >
                        How we work
                    </p>
                    <p
                        class="xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70 max-w-[405px]"
                    >
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                        do eiusmod tempor.
                    </p>
                    <div class="flex xs:flex-row md:flex-row items-center gap-4">
                        <div>
                            <p
                                class="xs:text-[14px] font-sans md:text-[18px] font-semibold leading-[64px] text-[#2405F2]"
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
                <!-- 4 steps main div -->
                <div
                    class="flex gap-[25px] xs:flex-col lg:flex-row md:items-center md:justify-center"
                >
                    <!-- div 1 -->
                    <div class="flex xs:flex-col lg:flex-col gap-12 md:flex-row">
                        <!-- Strategy -->
                        <div>
                            <img src={pointer1} alt="" />
                            <p
                                class="xs:text-[24px] font-sans md:text-[32px] font-medium leading-[48px]"
                            >
                                Strategy
                            </p>
                            <p
                                class="max-w-[303px] xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70"
                            >
                                Euismod faucibus turpis eu gravida mi. Pellentesque
                                et velit aliquam .
                            </p>
                        </div>
                        <!-- Wireframing -->
                        <div>
                            <img src={pointer2} alt="" />
                            <p
                                class="xs:text-[24px] font-sans md:text-[32px] font-medium leading-[48px]"
                            >
                                Wireframing
                            </p>
                            <p
                                class="max-w-[303px] xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70"
                            >
                                Euismod faucibus turpis eu gravida mi. Pellentesque
                                et velit aliquam .
                            </p>
                        </div>
                    </div>
                    <!-- div 2 -->
    
                    <div class="flex lg:flex-col gap-12 md:flex-row xs:flex-col">
                        <!-- Design -->
                        <div>
                            <img src={pointer3} alt="" />
                            <p
                                class="xs:text-[24px] font-sans md:text-[32px] font-medium leading-[48px]"
                            >
                                Design
                            </p>
                            <p
                                class="max-w-[303px] xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70"
                            >
                                Euismod faucibus turpis eu gravida mi. Pellentesque
                                et velit aliquam .
                            </p>
                        </div>
                        <!-- Development -->
                        <div>
                            <img src={pointer4} alt="" />
                            <p
                                class="xs:text-[24px] font-sans md:text-[32px] font-medium leading-[48px]"
                            >
                                Development
                            </p>
                            <p
                                class="max-w-[303px] xs:text-[12px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70"
                            >
                                Euismod faucibus turpis eu gravida mi. Pellentesque
                                et velit aliquam .
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>    
    </div>

</div>

<!-- <div class="m-auto max-w-[1600px]"> -->
   
    <div class="m-auto max-w-[1600px] flex justify-center">

    <!-- View our projects -->
    <!-- View our projects :Main Div -->

    <div class="flex flex-col xs:py-6 md:py-22 lg:py-32 xs:px-4 xs:gap-2 md:gap-6 lg:gap-16 max-w-[1280px] justify-center">
        <!-- div 1 -->
        <div class="flex flex-row justify-between">
            <p
                class="xs:text-[14px] font-sans lg:text-[48px] md:text-[24px] font-semibold leading-[64px]"
            >
                View our projects
            </p>
            <div class="flex flex-row justify-center items-center gap-4">
                <a
                    href="/"
                    class="xs:text-[14px] font-sans md:text-[16px] font-medium leading-[28px]  cursor-pointer"
                    >View More</a
                >
                <svg
                class=" cursor-pointer"
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
        <!-- div 2 -->
        <div class="flex md:flex-row gap-8 xs:flex-col xs:items-center">
            <div>
                <img src={ViewProjects} alt="" />
            </div>
            <div>
                <img src={HoverOverlay} alt="" />
                <img src={Card} alt="" />
            </div>
        </div>
    </div>
</div>
    <!-- Features -->
    <!-- Features : Main div -->

    <div class="bg-[#F4F6FC] xs:py-6 md:py-22 lg:py-32  flex flex-col gap-12">
        <div class="flex flex-col justify-center items-center">
            <p class="font-sans text-[16px] font-medium leading-[28px]">
                Features
            </p>
            <p
                class="xs:text-[24px] font-sans md:text-[48px] font-semibold xs:leading-9 md:px-6 px-4 md:leading-[64px] max-w-[630px] text-center"
            >
                Design that solves problems, one product at a time
            </p>
        </div>
        <!-- Cards Div -->
        <div class="flex justify-center xs:px-5">
            <!-- Cards -->
            <div
                class="grid md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-3 gap-x-[32px] gap-y-[24px]"
            >
                {#each cards as card}
                    <div id="cards">
                        <div
                            class="bg-white max-w-[405px] lg:px-12 xs:px-4 md:px-6 px-4 lg:py-12 md:py-8 py-6  flex flex-col gap-4"
                        >
                            <div>
                                {@html card.svg}
                                <p
                                    class="pb-[12px] font-sans text-[24px] font-medium leading-[36px]"
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
    </div>
    <!-- What our clients say about us -->
        <!-- What our clients say about us:Parent Div -->
        <!-- <div class="flex flex-row justify-center"> -->

    <div class="flex xs:flex-col xs: px-4 lg:flex-row justify-center xs:py-6 md:py-7 lg:py-32 xs:gap-5 md:gap-6 lg:gap-28 bg-[#F4F6FC]/[0.5]">
        <!-- child 1 -->
        <div class="">
            <p class="xs:text-[28px] font-sans md:text-[38px] font-semibold leading-[56px]  ">What our clients say about us</p>
            <p  class="xs:text-[14px] font-sans md:text-[16px] font-normal leading-[28px] opacity-70 ">Lorem ipsum dolor sit amet, consectetur adipiscing elit sed.</p>

        </div>
                <!-- child 2 -->

        <div class="flex flex-col md:gap-12">
            <p class="xs:text-[18px] font-sans md:text-[32px] font-medium leading-[48px] max-w-[830px]">"The best agency we’ve worked with so far. They understand our product and are able to add new features with a great focus."</p>
            <div class="flex flex-row justify-between">
                <div class="flex flex-row  gap-[9.63px] justify-center items-center">
                    <div>
                        <img src={JennyWilson} alt=""/>
                    </div>
                    <div>
                        <p class="xs:text-[14px] font-sans md:text-[18px] font-medium leading-[32px]">Jenny Wilson</p>
                        <p class="xs:text-[12px] font-sans md:text-[12px] font-medium leading-[28px]" >Vice President</p>

                    </div>

                </div>
                <div><svg class="cursor-pointer" xmlns="http://www.w3.org/2000/svg" width="109" height="48" viewBox="0 0 109 48" fill="none">
                    <ellipse cx="84.1002" cy="24" rx="24.0997" ry="24" fill="#5239FA"/>
                    <path d="M78.4146 35L77.0005 31.7805L86.031 24.0894L77.0005 16.2195L78.4146 13L90.0005 23.374V25.1626L78.4146 35Z" fill="white"/>
                    <ellipse cx="24.6" cy="24" rx="24.5997" ry="24" transform="rotate(-180 24.6 24)" fill="white"/>
                    <path opacity="0.6" d="M29.1796 13L30.623 16.2195L21.4052 23.9106L30.623 31.7805L29.1796 35L17.3533 24.626L17.3533 22.8374L29.1796 13Z" fill="#282938"/>
                  </svg></div>
            </div>
        </div>

    </div>
    <!-- Frequently asked questions -->
    <!-- FAQs Parent Div -->
    <div class="flex lg:flex-row justify-center lg:py-32 xs:flex-col xs:items-center  md:items-start lg:gap-[136px] xs:gap-[50px] xs:px-5">
    <!-- FAQs child Div 1 -->
    <div>
        <p class="xs:text-[18px] md:text-[24px] font-sans lg:text-[38px] font-semibold leading-[56px]">Frequently asked questions</p>
        <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[18px] font-medium leading-[32px] text-[#2405F2]/[0.8700000047683716]">Contact us for more info</p>
    </div>
        <!-- FAQs child Div 2 -->
<div >
    <div class="flex flex-col">
    <div class="flex flex-row xs:gap-[29px] md:gap-[59px]  border-b-2">
        <p class="text-[#2405F2] xs:text-[14px] font-sans md:text-[24px] font-medium leading-[36px]">01</p>
        <div>
        <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[24px] font-medium leading-[36px]">How much time does it take?</p>
        <p  class="xs:text-[14px] font-sans lg:text-[18px] font-medium leading-[36px] opacity-[0.8700000047683716] max-w-[642px]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </div>
    <svg class="cursor-pointer" width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path opacity="0.7" d="M12.1495 13.1605L7.12057 8.1316L1.96717 13.285L0.711315 12.0292L5.86472 6.87575L0.835794 1.84682L1.84269 0.839932L6.87161 5.86886L12.025 0.715453L13.2809 1.9713L8.12746 7.12471L13.1564 12.1536L12.1495 13.1605Z" fill="#282938"/>
        </svg>
        
    </div>
    <!-- faq 2 -->
    <div class="flex justify-between items-center border-b-2 xs:py-2 md:py-5">
        <div class="flex xs:gap-5 md:gap-[53px]">
            <p class="text-[#2405F2] xs:text-[14px] font-sans md:text-[24px] font-medium leading-[36px]">02</p>
           
            <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[24px] font-medium leading-[36px]">What is your class naming convention?</p>

        </div>
        <!-- <p  class="xs:text-[14px] font-sans lg:text-[18px] font-medium leading-[36px] opacity-[0.8700000047683716]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> -->
    <div>
        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path opacity="0.7" d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z" fill="#282938"/>
            </svg>
        
    </div>  
    </div>
<!-- faq 3 -->
<div class="flex justify-between items-center border-b-2 md:py-5 xs:py-2">
    <div class="flex  xs:gap-5 md:gap-[53px]">
        <p class="text-[#2405F2] xs:text-[14px] font-sans md:text-[24px] font-medium leading-[36px]">03</p>
       
        <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[24px] font-medium leading-[36px]">How do you communicate?</p>

    </div>
    <!-- <p  class="xs:text-[14px] font-sans lg:text-[18px] font-medium leading-[36px] opacity-[0.8700000047683716]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> -->
<div>
    <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path opacity="0.7" d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z" fill="#282938"/>
        </svg>
    
</div>  
</div>
    <!-- faq 4 -->
    <div class="flex justify-between items-center border-b-2 md:py-5 xs:py-2">
        <div class="flex  xs:gap-5 md:gap-[53px]">
            <p class="text-[#2405F2] xs:text-[14px] font-sans md:text-[24px] font-medium leading-[36px]">04</p>
           
            <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[24px] font-medium leading-[36px]">I have a bigger project. Can you handle it?</p>

        </div>
        <!-- <p  class="xs:text-[14px] font-sans lg:text-[18px] font-medium leading-[36px] opacity-[0.8700000047683716]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> -->
    <div>
        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path opacity="0.7" d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z" fill="#282938"/>
            </svg>
        
    </div>  
    </div>
    <!-- faq 5 -->
    <div class="flex justify-between items-center border-b-2 md:py-5 xs:py-2">
        <div class="flex  xs:gap-5 md:gap-[53px]">
            <p class="text-[#2405F2] xs:text-[14px] font-sans md:text-[24px] font-medium leading-[36px]">05</p>
           
            <p class="xs:text-[14px] md:text-[18px] font-sans lg:text-[24px] font-medium leading-[36px]">What is your class naming convention?</p>

        </div>
        <!-- <p  class="xs:text-[14px] font-sans lg:text-[18px] font-medium leading-[36px] opacity-[0.8700000047683716]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> -->
    <div>
        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path opacity="0.7" d="M16 8.71198H8.88802V16H7.11198V8.71198H0V7.28802H7.11198V0H8.88802V7.28802H16V8.71198Z" fill="#282938"/>
            </svg>
        
    </div>  
    </div>
   
    
</div>
</div>
</div>
<!-- Send inquiry parent div-->
<div class="flex justify-center ">
    <!-- child div -->
    <div class="flex justify-center items-center xs:flex-col lg:flex-row bg-[#1C1E53] ">
        <div class="relative"> 

            <img src={Group1} alt=""/>
            <div class="absolute text-black max-w-[464px] md:left-[104px] md:top-24 xs:left-[30px] top-4 flex flex-col md:gap-[24px] xs:gap-[10px]">
                <p class="xs:text-[14px] font-sans md:text-[54px] font-semibold leading-[74px] text-white">Building stellar websites for early startups</p>
                <p class="xs:text-[12px] font-sans md:text-[16px] font-medium leading-[28px] text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua ut enim.</p>
            </div>

        </div>
        <div class="flex flex-col justify-center items-center lg:px-24 xs:px-5 xs py-5 lg:py-0">
            <div class="flex flex-col gap-10  lg:gap-8 ">
                <div>
                <p class="xs:text-[20px] font-sans md:text-[32px] font-medium leading-[48px] text-white">Send inquiry</p>
                <p class=" max-w-[432px] font-sans md:text-[16px] font-medium leading-[28px] text-white">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore.</p>
            </div>
            <!-- Form Inputs -->
                <div class="flex flex-col gap-4 max-w-[432px]">
                    <input type="text" placeholder="Your Name" class="bg-transparent border-2 rounded border-gray-600 py-[18px] px-8 "/>
                    <input type="text" placeholder="Email " class="bg-transparent border-2 rounded border-gray-600 py-[18px] px-8 w-full"/>
                    <input type="text" placeholder=" Paste your Figma design URL" class="bg-transparent border-2 rounded border-gray-600 py-[18px] px-8 w-full"/>

                </div>
                <!-- Button -->
                <button class="md:max-w-[432px] bg-[#FCD980] rounded-full xs:py-[15px] md:px-[51px] md:py-[15px] hover:hover:bg-[rgb(223,184,87)] transition ease-in-out duration-700">Send an Inquiry</button>
                <div class="flex flex-row justify-center items-center gap-2">
                    <a class="font-sans md:text-[18px] font-medium leading-[32px] text-white cursor-pointer" href="/">Get in touch with us</a>
                    <svg class=" cursor-pointer" width="25" height="12" viewBox="0 0 25 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M24.5303 6.53033C24.8232 6.23744 24.8232 5.76256 24.5303 5.46967L19.7574 0.696699C19.4645 0.403806 18.9896 0.403806 18.6967 0.696699C18.4038 0.989593 18.4038 1.46447 18.6967 1.75736L22.9393 6L18.6967 10.2426C18.4038 10.5355 18.4038 11.0104 18.6967 11.3033C18.9896 11.5962 19.4645 11.5962 19.7574 11.3033L24.5303 6.53033ZM0 6.75H24V5.25H0V6.75Z" fill="#F4F6FC"/>
                        </svg>
                        
                </div>
            </div>
        </div>

    </div>
</div>

  <!-- Our blog -->
  <div
  class="flex flex-col justify-start xs:pt-20 md:pt-[128px] max-w-[1280px] m-auto xs:items-center md:items-center lg:items-start xs:px-5"
>
  <p class="xs:text-[30px] font-sans text-[48px] font-semibold leading-[64px]">
      Our blog
  </p>
  <!-- Cards -->

  <div
      class="flex xs:flex-col md:gap-[50px] sm:flex-col sm:items-center md:flex-col md:items-center md:justify-center md:m-auto lg:flex-row"
      id="cards"
  >
      <div class="bg-white max-w-[405px] md:pb-[48px] md:pt-[58px] xs:pb-[28px] xs:pt-[38px] flex flex-col gap-3">
          <img src={businessman} alt="" />

          <p
              class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              19 Jan 2022
          </p>
          <p class="font-sans xs:text-[16px] md:text-[24px] font-medium leading-[36px]">
              How one Webflow user grew his single person consultancy
              from $0-100K in 14 months
          </p>
          <p
              class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              See how pivoting to Webflow changed one person’s sales
              strategy and allowed him to attract
          </p>
          <div class="flex flex-row items-center gap-[14px] pt-3">
              <a
                  href="/"
                  class="font-sans text-[16px] font-normal leading-[28px]"
                  >Read More</a
              >
              <svg
              class="cursor-pointer"
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

      <div class="bg-white max-w-[405px] md:pb-[48px] md:pt-[58px] xs:pb-[28px] xs:pt-[38px] flex flex-col gap-3">
          <img src={macbook} alt="" />

          <p
              class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              19 Jan 2022
          </p>
          <p class="font-sans  xs:text-[16px] md:text-[24px] font-medium leading-[36px]">
              How one Webflow user grew his single person consultancy
              from $0-100K in 14 months
          </p>
          <p
              class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              See how pivoting to Webflow changed one person’s sales
              strategy and allowed him to attract
          </p>
          <div class="flex flex-row items-center gap-[14px] pt-3">
              <a
                  href="/"
                  class="font-sans text-[16px] font-normal leading-[28px]"
                  >Read More</a
              >
              <svg
              class=" cursor-pointer"
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
      <div class="bg-white max-w-[405px] md:pb-[48px] md:pt-[58px] xs:pb-[28px] xs:pt-[38px] flex flex-col gap-3">
          <img src={applemonitors} alt="" />

          <p
              class="font-sans text-[16px] font-medium leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              19 Jan 2022
          </p>
          <p class="font-sans xs:text-[16px] md:text-[24px] font-medium leading-[36px]">
              How one Webflow user grew his single person consultancy
              from $0-100K in 14 months
          </p>
          <p
              class="font-sans text-[16px] font-normal leading-[28px] text-[#282938]/[0.699999988079071]"
          >
              See how pivoting to Webflow changed one person’s sales
              strategy and allowed him to attract
          </p>
          <div class="flex flex-row items-center gap-[14px] pt-3">
              <a
                  href="/"
                  class="font-sans text-[16px] font-normal leading-[28px]"
                  >Read More</a
              >
              <svg
              class=" cursor-pointer"
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
<!-- </div> -->

<!-- </div> -->
<!-- </div> -->

<Footer />