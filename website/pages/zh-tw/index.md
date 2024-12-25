---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: ""
googleSiteVerification: "Xddhfnp6S__WbmOQIBRh3NGoA6r0qQSofEtdht6L7ao"

title: "Uncle Yu Restaurant 永康又一家 - Best Food Today"
favicon: "favicon.ico"
logo: "logo.webp"
primaryColor: "#F11B20" # logo color
secondaryColor: "#F7D389"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=e207865d-77a8-46ab-8b4a-00dee8b31224"
tableReservationLink: ""
tel: "510-475-8087"
trackingNum: ""

# banner:
#   text:
#     # - boldText: "🥳 Special Offer"
#     - boldText: "A free 汽水 Can Soda"
#     - text: "on order $35+"
#     - smText: ""
#   # add more text...

# header
header:
  logoSize: 75
  logoSizeOnMobile: 60
  textAfterLogo:
    text: ""
    size: 16
    color: ""
  showTextAfterLogoOnMobile: false
  logoOnMobile: "" # e.g., 'logo.png'. Set a logo for mobile that is different from the desktop.

  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "首頁", link: "/zh-tw" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "在線訂餐"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=e207865d-77a8-46ab-8b4a-00dee8b31224"
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
  # hero
  - type: "hero"
    id: ""
    height: "80" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
    bgImg: "Uncle Yu Restaurant11.jpeg"
    bgColor: "#000000"
    bgOpacity: "0.2" # 0~1
    title:
      - "Uncle Yu Restaurant"
      - "永康又一家"
    titleColor: "#ffffff"
    description:
      - "Union City 的亞洲及中國美食"
    descriptionColor: "#ffffff"
    isTextAlignCenter: true
    # title2:
    #   - ""
    # title2Color: "#ffffff"
    # description2:
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: "在線訂餐"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=e207865d-77a8-46ab-8b4a-00dee8b31224"
    btn2Text: ""
    btn2Href: ""

    bannerImg: "sample.webp"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "我們提供在線訂餐"

  # # Video
  #   - type: "video"
  #     id: ""
  #     title:
  #       - "Lorem ipsum dolor sit amet"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et"
  #     videoType: "gjw" # vimeo | gjw | youtube
  #     videoId:
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #     isOnlyDisplayOnMobile: false

  # Gallery
  - type: "gallery"
    id: "gallery"
    mode: 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Uncle Yu Restaurant"
      - "永康又一家的美食"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  #     # Gallery
  #   - type: "gallery"
  #     id: "gallery"
  #     mode: 3 # 1 - 3
  #     bgImg: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "Uncle Yu Restaurant 永康又一家菜單"
  #     titleColor: "#000000"
  #     description:
  #       - ""
  #     descriptionColor: "#333333"
  #     folderPath: "gallery2"
  #     showImgName: false # true | false
  #     imgNameColor: "#000000"
  #     menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # textBlock - only title
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "關於我們"
    titleColor: "#000000"
    description:
      - "Uncle Yu Restaurant 永康又一家於1995年在 Union City 成立。Uncle Yu Restaurant 永康又一家專營正宗中餐，提供品質優良、味道可口的餐點。Uncle Yu Restaurant 永康又一家的老闆Ginny在中國出生，15歲時在香港開始學習烹飪。在香港積累了8年的烹飪經驗後，Ginny 移居美國，在Newark開了第一家餐廳「永康海鮮酒家」，之後在Fremont開了「新永康海鮮酒家」。"
      - "他成功的秘訣在於專注食物的品質，每天都在當地採購新鮮的農產品。Uncle Yu Restaurant 永康又一家的特色菜有核桃雞、蒙古牛肉和烤肉炒麵。現在餐廳也開始提供冰淇淋。歡迎您隨時光臨Union City到餐廳享受美食。餐廳從Hwy 880 離開Whipple Rd，餐廳就在 Industrial Pkwy SW 的旁邊。"

    descriptionColor: ""

  # feature - imgWithText
  - type: "feature"
    noMarginTop: true
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "imgWithText" # video | imgWithText | imgBg
    title:
      - "歡迎來 Uncle Yu Restaurant 永康又一家"
    titleColor: "#000000"
    description:
      - "在 Uncle Yu Restaurant 永康又一家，我們非常高興為顧客提供正宗美味的中國菜。"
    descriptionColor: "#000000"
    isTextAlignCenter: true

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: ""
    btn1Href: ""
    btn2Text: ""
    btn2Href: ""

    bannerImg: "uncle yu.webp"
    imgPosition: "imgRight" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "sm" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - map
  #   - type: "feature"
  #     id: ""
  #     noMarginTop: false
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Store 2 : Washington St"
  #     titleColor: "#000000"
  #     description:
  #       - "Opening Hours: "
  #       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: true
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: true
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: true
  #     btn1Text: "Order online from Washington St Store"
  #     btn1Href: "#"
  #     btn2Text: ""
  #     btn2Href: ""

  #     map: true
  #     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
  #     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
  #     addTelBtn: true
  #     tel: "12345678"
  #     telInsteadText: "Call: (123) 456-7890"
  #     telTrackingNum: "" # if there are two phone numbers
  #     tel2: "876543210" # if there are two phone numbers
  #     tel2InsteadText: "Call: (876) 543-2100"
  #     telTrackingNum2: "" # if there are two phone numbers
  #     getDirectionBtnInsteadText: ""
  #     imgPosition: "" # imgLeft | imgRight

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "About Us"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  # textBlock - Information
  - type: "textBlock"
    noMarginTop: false
    id: ""
    # bgImg: "/Uncle Yu Restaurant11.jpeg"
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title:
      - "新功能! 在線訂餐"
    titleColor: "#ffffff"
    description:
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/Po55ANqgqeUJw9WS9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3160.569173689629!2d-122.07087332412405!3d37.61229737202664!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f95cca8b233ad%3A0x1c42f42664925283!2zVW5jbGUgWXUgUmVzdGF1cmFudCDmsLjlurflj4jkuIDlrrY!5e0!3m2!1szh-CN!2sjp!4v1723253578300!5m2!1szh-CN!2sjp"
    addTelBtn: true
    tel: ""
    telInsteadText: "電話：510-475-8087"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "導航去餐廳"

#  # The modal will only appear once within 30 minutes."
#   - type: "modal"
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title:
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description:
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: ""
  bgColor: "#f3f4f6"
  bgOpacity: "1" # 0~1
  textColor: "#000000" # default white

  openingHoursInsteadText: "營業時間"
  openingHours:
    - "週一, 週三 - 週日"
    - "10:00 AM - 9:00 PM"
    - "週二"
    - "休業"

  isLogo: true
  logoSize: 100
  logoSizeOnMobile: 80
  # menu:
  #   - { text: "Home", link: "/" }
  #   - { text: "Gallery", link: "#gallery" }
  #   - { text: "About Us", link: "/#about-us" }
  #   - { text: "Contact Us", link: "/#contact-us" }
  #   - { text: "中文", link: "/zh-tw" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  doorDash: false
  doorDashLink: ""
  uberEats: false
  uberEatsLink: ""

  acceptedPaymentMethodsInsteadText: "支付方式"
  paymentMethod: "visa,amex,applePay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  address:
    - address: "30059 Industrial Pkwy SW, Union City, CA 94587"
      url: "https://maps.app.goo.gl/Po55ANqgqeUJw9WS9"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Uncle Yu Restaurant 永康又一家 | aUnion City的一家中餐館"
  metaDescription: "Union City 的永康又一家 Uncle Yu 餐館提供各式正宗的中式佳餚。邀請您與家人朋友一起享受難忘的用餐體驗。立即在線訂購！"
  canonicalHref: "https://www.uncleyurestaurant-order.com/" # https://example.com/

  locale: "zh_TW" # zh_TW | zh_CN | ja_JP
---

<!-- hello world -->
