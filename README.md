Directory structure:
└── ayushd15-full-stack-e-commerce-platform/
    ├── admin/
    │   ├── README.md
    │   ├── eslint.config.js
    │   ├── index.html
    │   ├── package.json
    │   ├── postcss.config.js
    │   ├── tailwind.config.js
    │   ├── vite.config.js
    │   ├── public/
    │   │   ├── patern.webp
    │   │   └── shop-illustration.webp
    │   └── src/
    │       ├── App.css
    │       ├── App.jsx
    │       ├── firebase.jsx
    │       ├── index.css
    │       ├── main.jsx
    │       ├── responsive.css
    │       ├── Components/
    │       │   ├── Badge/
    │       │   │   └── index.jsx
    │       │   ├── DashboardBoxes/
    │       │   │   └── index.jsx
    │       │   ├── Header/
    │       │   │   └── index.jsx
    │       │   ├── OtpBox/
    │       │   │   └── index.jsx
    │       │   ├── ProgressBar/
    │       │   │   └── index.jsx
    │       │   ├── SearchBox/
    │       │   │   └── index.jsx
    │       │   ├── Sidebar/
    │       │   │   └── index.jsx
    │       │   └── UploadBox/
    │       │       └── index.jsx
    │       ├── Pages/
    │       │   ├── Address/
    │       │   │   └── addAddress.jsx
    │       │   ├── Banners/
    │       │   │   ├── addBannerV1.jsx
    │       │   │   ├── bannerList2.jsx
    │       │   │   ├── bannerList2_AddBanner.jsx
    │       │   │   ├── bannerList2_Edit_Banner.jsx
    │       │   │   ├── bannerV1List.jsx
    │       │   │   └── editBannerV1.jsx
    │       │   ├── Blog/
    │       │   │   ├── addBlog.jsx
    │       │   │   ├── editBlog.jsx
    │       │   │   └── index.jsx
    │       │   ├── Categegory/
    │       │   │   ├── addCategory.jsx
    │       │   │   ├── addSubCategory.jsx
    │       │   │   ├── editCategory.jsx
    │       │   │   ├── EditSubCatBox.jsx
    │       │   │   ├── index.jsx
    │       │   │   └── subCatList.jsx
    │       │   ├── ChangePassword/
    │       │   │   └── index.jsx
    │       │   ├── Dashboard/
    │       │   │   └── index.jsx
    │       │   ├── ForgotPassword/
    │       │   │   └── index.jsx
    │       │   ├── HomeSliderBanners/
    │       │   │   ├── addHomeSlide.jsx
    │       │   │   ├── editHomeSlide.jsx
    │       │   │   └── index.jsx
    │       │   ├── Login/
    │       │   │   └── index.jsx
    │       │   ├── ManageLogo/
    │       │   │   └── index.jsx
    │       │   ├── Orders/
    │       │   │   └── index.jsx
    │       │   ├── Products/
    │       │   │   ├── addProduct.jsx
    │       │   │   ├── addRAMS.jsx
    │       │   │   ├── addSize.jsx
    │       │   │   ├── addWeight.jsx
    │       │   │   ├── editProduct.jsx
    │       │   │   ├── index.jsx
    │       │   │   └── productDetails.jsx
    │       │   ├── Profile/
    │       │   │   └── index.jsx
    │       │   ├── SignUp/
    │       │   │   └── index.jsx
    │       │   ├── Users/
    │       │   │   └── index.jsx
    │       │   └── VerifyAccount/
    │       │       └── index.jsx
    │       └── utils/
    │           └── api.js
    ├── client/
    │   ├── README.md
    │   ├── eslint.config.js
    │   ├── index.html
    │   ├── package.json
    │   ├── postcss.config.js
    │   ├── tailwind.config.js
    │   ├── vite.config.js
    │   ├── public/
    │   │   ├── banner1.webp
    │   │   ├── banner2.webp
    │   │   ├── banner3.webp
    │   │   ├── banner5.webp
    │   │   └── banner6.webp
    │   └── src/
    │       ├── App.css
    │       ├── App.jsx
    │       ├── firebase.jsx
    │       ├── index.css
    │       ├── main.jsx
    │       ├── responsive.css
    │       ├── components/
    │       │   ├── AccountSidebar/
    │       │   │   └── index.jsx
    │       │   ├── AdsBannerSlider/
    │       │   │   └── index.jsx
    │       │   ├── AdsBannerSliderV2/
    │       │   │   └── index.jsx
    │       │   ├── Badge/
    │       │   │   └── index.jsx
    │       │   ├── BannerBox/
    │       │   │   └── index.jsx
    │       │   ├── bannerBoxV2/
    │       │   │   ├── index.jsx
    │       │   │   └── style.css
    │       │   ├── BlogItem/
    │       │   │   └── index.jsx
    │       │   ├── CartPanel/
    │       │   │   └── index.jsx
    │       │   ├── CategoryCollapse/
    │       │   │   └── index.jsx
    │       │   ├── Footer/
    │       │   │   └── index.jsx
    │       │   ├── Header/
    │       │   │   ├── index.jsx
    │       │   │   └── Navigation/
    │       │   │       ├── CategoryPanel.jsx
    │       │   │       ├── index.jsx
    │       │   │       ├── MobileNav.jsx
    │       │   │       └── style.css
    │       │   ├── HomeCatSlider/
    │       │   │   └── index.jsx
    │       │   ├── HomeSlider/
    │       │   │   └── index.jsx
    │       │   ├── HomeSliderV2/
    │       │   │   └── index.jsx
    │       │   ├── LoadingSkeleton/
    │       │   │   └── bannerLoading.jsx
    │       │   ├── OtpBox/
    │       │   │   └── index.jsx
    │       │   ├── ProductDetails/
    │       │   │   └── index.jsx
    │       │   ├── ProductItem/
    │       │   │   ├── index.jsx
    │       │   │   └── style.css
    │       │   ├── ProductItemListView/
    │       │   │   ├── index.jsx
    │       │   │   └── style.css
    │       │   ├── ProductLoading/
    │       │   │   ├── index.jsx
    │       │   │   └── productLoadingGrid.jsx
    │       │   ├── ProductsSlider/
    │       │   │   └── index.jsx
    │       │   ├── ProductZoom/
    │       │   │   └── index.jsx
    │       │   ├── QtyBox/
    │       │   │   └── index.jsx
    │       │   ├── Search/
    │       │   │   ├── index.jsx
    │       │   │   └── style.css
    │       │   └── Sidebar/
    │       │       ├── index.jsx
    │       │       └── style.css
    │       ├── Pages/
    │       │   ├── Cart/
    │       │   │   ├── cartItems.jsx
    │       │   │   └── index.jsx
    │       │   ├── Checkout/
    │       │   │   └── index.jsx
    │       │   ├── ForgotPassword/
    │       │   │   └── index.jsx
    │       │   ├── Home/
    │       │   │   ├── index - Copy.jsx
    │       │   │   └── index.jsx
    │       │   ├── Login/
    │       │   │   └── index.jsx
    │       │   ├── MyAccount/
    │       │   │   ├── addAddress.jsx
    │       │   │   ├── address.jsx
    │       │   │   ├── addressBox.jsx
    │       │   │   └── index.jsx
    │       │   ├── MyList/
    │       │   │   ├── index.jsx
    │       │   │   └── myListItems.jsx
    │       │   ├── Orders/
    │       │   │   ├── failed.jsx
    │       │   │   ├── index.jsx
    │       │   │   └── success.jsx
    │       │   ├── ProductDetails/
    │       │   │   ├── index.jsx
    │       │   │   └── reviews.jsx
    │       │   ├── ProductListing/
    │       │   │   └── index.jsx
    │       │   ├── Register/
    │       │   │   └── index.jsx
    │       │   ├── Search/
    │       │   │   └── index.jsx
    │       │   └── Verify/
    │       │       └── index.jsx
    │       └── utils/
    │           └── api.js
    └── server/
        ├── index.js
        ├── package.json
        ├── config/
        │   ├── connectDb.js
        │   ├── emailService.js
        │   └── sendEmail.js
        ├── controllers/
        │   ├── address.controller.js
        │   ├── bannerList2.controller.js
        │   ├── bannerV1.controller.js
        │   ├── blog.controller.js
        │   ├── cart.controller.js
        │   ├── category.controller.js
        │   ├── homeSlider.controller.js
        │   ├── logo.controller.js
        │   ├── mylist.controller.js
        │   ├── order.controller.js
        │   ├── product.controller.js
        │   └── user.controller.js
        ├── middlewares/
        │   ├── auth.js
        │   └── multer.js
        ├── models/
        │   ├── address.model.js
        │   ├── bannerList2.model.js
        │   ├── bannerV1.model.js
        │   ├── blog.model.js
        │   ├── cartProduct.modal.js
        │   ├── category.modal.js
        │   ├── homeSlider.modal.js
        │   ├── logo.model.js
        │   ├── myList.modal.js
        │   ├── order.model.js
        │   ├── product.modal.js
        │   ├── productRAMS.js
        │   ├── productSIZE.js
        │   ├── productWEIGHT.js
        │   ├── reviews.model.js.js
        │   └── user.model.js
        ├── route/
        │   ├── address.route.js
        │   ├── bannerList2.route.js
        │   ├── bannerV1.route.js
        │   ├── blog.route.js
        │   ├── cart.route.js
        │   ├── category.route.js
        │   ├── homeSlides.route.js
        │   ├── logo.route.js
        │   ├── mylist.route.js
        │   ├── order.route.js
        │   ├── product.route.js
        │   └── user.route.js
        └── utils/
            ├── generatedAccessToken.js
            ├── generatedRefreshToken.js
            ├── orderEmailTemplate.js
            └── verifyEmailTemplate.js
