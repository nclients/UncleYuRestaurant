---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
tag: "GTM-"
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
tel: "510 475 8087"
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
  logoSize: 45
  textAfterLogo: 
    text: "Uncle Yu Restaurant 永康又一家"
    size: 16
    color: ""
  showTextAfterLogoOnMobile: false
  logoOnMobile: "" # e.g., 'logo.png'. Set a logo for mobile that is different from the desktop.
  
  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
  
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "Online Order"
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
      - "Uncle Yu Restaurant 永康又一家"
    titleColor: "#ffffff"
    description: 
      - "ASIAN & CHINESE FOOD IN UNION CITY"
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

    btn1Text: ""
    btn1Href: "" 
    btn2Text: "" 
    btn2Href: "" 

    bannerImg: "sample.webp"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "We offer Takeout"

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
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Food At Uncle Yu Restaurant"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    # Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "Uncle Yu Restaurant Menu"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


# textBlock - only title
  - type: "textBlock" 
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - "About Us"
    titleColor: "#000000"
    description: 
      - "Uncle Yu Restaurant is Established in 1995 in Union City. Uncle Yu is specialize in authentic Chinese food by offering meals of excellent quality and delicious taste. Uncle Yu’s owner Ginny was born in China and started cooking in Hong Kong when he was 15 years old. After 8 years’ cooking experience in Hong Kong, Ginny moved to the US and opened his first restaurant “Yong Kang Seafood Restaurant” in Newark and then “New Yong Kang Seafood Restaurant” in Fremont."
      - "The secret for his success is the food quality by purchasing all produce everyday fresh and locally. Some specialties in Uncle Yu’s are: Walnut Chicken, Mongolian Beef and BBQ Pork Chow Mein. Now we also serve ice cream. You are always welcome to Union City and Take off Whipple Rd from Hwy 880, Uncle Yu is just located off Industrial Pkwy SW. "
    


    descriptionColor: ""

# feature - imgWithText
  - type: "feature" 
    noMarginTop: true
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "imgWithText" # video | imgWithText | imgBg
    title: 
      - "Welcome To Uncle Yu Restaurant"
    titleColor: "#000000"
    description: 
      - "At Uncle Yu Restaurant 永康又一家, we pride ourselves on serving our customers delicious genuine dishes like: Asian, Chinese."
    descriptionColor: "#000000"

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
    bgImg: "Uncle Yu Restaurant11.jpeg"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title: 
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description: 
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"
  
# map  
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/Po55ANqgqeUJw9WS9"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3160.569173689629!2d-122.07087332412405!3d37.61229737202664!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f95cca8b233ad%3A0x1c42f42664925283!2zVW5jbGUgWXUgUmVzdGF1cmFudCDmsLjlurflj4jkuIDlrrY!5e0!3m2!1szh-CN!2sjp!4v1723253578300!5m2!1szh-CN!2sjp"
    addTelBtn: true
    tel: "510 475 8087"
    telInsteadText: "Tel：510 475 8087"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: ""
 
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

  openingHoursInsteadText: ""
  openingHours: 
    - "Monday:"
    - "10:00 AM - 9:00 PM"
    - "Tuesday:"
    - "Close"
    - "Wednesday - Sunday:"
    - "10:00 AM - 9:00 PM"
  
  isLogo: true
  logoSize: 60
 
  # menu:
  #   - { text: "Home", link: "/" }
  #   - { text: "Gallery", link: "#gallery" }
  #   - { text: "About Us", link: "/#about-us" }
  #   - { text: "Contact Us", link: "/#contact-us" }
  #   - { text: "中文", link: "/zh-cn" }

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

  acceptedPaymentMethodsInsteadText: ""
  paymentMethod: "visa,amex,cash,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: ""
  metaDescription: "" 
  keywords: ""
  img: ""
  thisPageUrl: ""
  locale: "en_US" # zh_TW | zh_CN
---
<!-- hello world -->