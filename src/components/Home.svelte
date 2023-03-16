<main class="home">
    <div class="container">
        <div class="left">
            <img class="product" src="/images/image-product-desktop.jpg" alt="">
        </div>
        <div class="right">
            <div class="intro">PERFUME</div>
            <h1 class="heading">Gabrielle Essence Eau De Parfum</h1>
            <div class="text">
                A floral, solar and voluptuous interpretation composed by Olivier Polge, Perfumer-Creator for the House of CHANEL.
            </div>
            <div class="price">
                $149.99
                <div class="old_price">$169.99</div>
            </div>
            <div class="add_btn">
                <img class="cart" src="/images/icon-cart.svg" alt="">
                <div class="add_text">Add to Cart</div>
            </div>
        </div>
    </div>
</main>

<style>
    .home {
        @apply w-screen h-screen flex justify-center items-center bg-[#f2ebe3];
    }
    .container {
        @apply w-[600px] h-[450px] flex flex-row rounded-[15px] bg-[#ffffff];
    }
    .left {
        @apply w-[300px] h-[100%];
    }
    .product {
        @apply w-[100%] h-[100%] rounded-tl-[15px] rounded-bl-[15px] object-cover;
    }
    .heading {
        @apply text-[36px] font-bold text-[#1c232b] leading-[42px] font-[Fraunces];
    }
    .intro {
        @apply tracking-[6px] font-medium text-[#6c7289] ;
    }
    .right {
        @apply w-[300px] h-[100%] p-[32px] flex flex-col gap-[16px];
    }
    .text {
        @apply text-[14px] text-[#6c7289];
    }
    .price {
        @apply text-[#3c8067] text-[32px] font-bold flex flex-row justify-between items-center font-[Fraunces];
    }
    .old_price {
        @apply text-[16px] text-[#6c7289] line-through font-medium;
    }
    .add_btn {
        @apply p-[14px] flex flex-row gap-[8px] justify-center items-center bg-[#3c8067] rounded-[10px] cursor-pointer duration-300;
    }
    .add_btn:hover {
        @apply bg-[#326b56];
    }
    .cart {
        @apply w-[16px] h-[16px];
    }
    .add_text {
        @apply text-[#ffffff] text-[16px] font-semibold;
    }
    @media only screen and (max-width: 600px) {
		.container {
            flex-direction: column;
			width: 350px;
            height: 600px;
            border-radius: 15px;
		}
        .left {
            width: 350px;
            height: 250px;
        }
        .right {
            width: 350px;
            height: 350px;
        }
        .product {
            border-radius: 15px 15px 0 0;
        }
        .right {
            padding: 24px;
        }
        .heading {
            font-size: 32px;
            line-height: 32px;
        }
        .price {
            font-size: 28px;
        }
        .add_btn {
            padding: 10px;
        }
	}
    @media only screen and (max-width: 350px) {
		.container {
            flex-direction: column;
			width: 300px;
            height: 600px;
            border-radius: 15px;
		}
        .left {
            width: 300px;
            height: 200px;
        }
        .right {
            width: 300px;
            height: 350px;
        }
        .product {
            border-radius: 15px 15px 0 0;
        }
        .right {
            padding: 24px;
        }
        .heading {
            font-size: 32px;
            line-height: 32px;
        }
        .price {
            font-size: 28px;
        }
        .add_btn {
            padding: 10px;
        }
	}
</style>