---
layout: "ssg-theme-astro/layouts/main.astro"  # This line of code should remain unchanged.
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
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "#about-us" }
    - { text: "Contact Us", link: "#contact-us" }
    - { text: "中文", link: "/zh-tw" }
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
      - "Uncle Yu Restaurant"
      - "永康又一家"
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

    btn1Text: "See MENU & Order"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=e207865d-77a8-46ab-8b4a-00dee8b31224" 
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
      - "永康又一家"
    titleColor: "#000000"
    description: 
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  #   # Gallery  
  # - type: "gallery"
  #   id: "gallery"
  #   mode: 3 # 1 - 3
  #   bgImg: ""
  #   bgColor: ""
  #   bgOpacity: "" # 0~1
  #   title: 
  #     - "Uncle Yu Restaurant Menu"
  #   titleColor: "#000000"
  #   description: 
  #     - ""
  #   descriptionColor: "#333333"
  #   folderPath: "gallery2"
  #   showImgName: false # true | false
  #   imgNameColor: "#000000"
  #   menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full


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
      - "Uncle Yu Restaurant 永康又一家 is Established in 1995 in Union City. Uncle Yu is specialize in authentic Chinese food by offering meals of excellent quality and delicious taste. Uncle Yu’s owner Ginny was born in China and started cooking in Hong Kong when he was 15 years old. After 8 years’ cooking experience in Hong Kong, Ginny moved to the US and opened his first restaurant “Yong Kang Seafood Restaurant” in Newark and then “New Yong Kang Seafood Restaurant” in Fremont."
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
      - "永康又一家"
    titleColor: "#000000"
    description: 
      - "At Uncle Yu Restaurant 永康又一家, we pride ourselves on serving our customers delicious genuine dishes like: Asian, Chinese."
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
    url: "https://maps.app.goo.gl/3RP42XH2HMkPq9Uc7"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3160.569173689625!2d-122.07087332390113!3d37.61229737202673!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f95cca8b233ad%3A0x1c42f42664925283!2sUncle%20Yu%20Restaurant!5e0!3m2!1sen!2sus!4v1726289171025!5m2!1sen!2sus"
    addTelBtn: true
    tel: ""
    telInsteadText: "Tel: 510-475-8087"
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
    - "Monday, Wednesday - Sunday"
    - "10:00 AM - 9:00 PM"
    - "Tuesday"
    - "Close"
   
  
  isLogo: true
  logoSize: 100
  logoSizeOnMobile: 80
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-tw" }

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
  paymentMethod: "visa,amex,applePay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  address: 
    - address: "30059 Industrial Pkwy SW, Union City, CA 94587"
      url: "https://maps.app.goo.gl/3RP42XH2HMkPq9Uc7"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Uncle Yu Restaurant 永康又一家 | a Chinese restaurant in Union city"
  metaDescription: "Uncle Yu Restaurant 永康又一家 in Union City offers a delightful array of authentic Chinese dishes. Join us for a memorable dining experience with family and friends.Online order Now！" 
  canonicalHref: "https://www.uncleyurestaurant-order.com/" # https://example.com/
    
  locale: "en_US" # zh_TW | zh_CN | ja_JP
   
#   # optional

#   thisPageUrl: "https://crabbynewark.com/" # https://example.com/
  
#   img: "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab.webp" # https://example.com/photos/1x1/photo.jpg
#   # keywords: "" # steak, restaurant, fine dining, New York

#   name: "Crabby Crabby Newark" # restaurant name

#   images:
#     - "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab.webp"  # https://example.com/photos/1x1/photo.jpg
#     - "https://crabbynewark.com/gallery/Tacos_2.webp"  # https://example.com/photos/1x1/photo.jpg
#     - "https://crabbynewark.com/gallery/Seafood_Whole_Dungeness_Crab_2.webp"  # https://example.com/photos/1x1/photo.jpg
  
#   address:
#     streetAddress: "6225 Jarvis Ave" # 148 W 51st St
#     addressLocality: "Newark" # New York
#     addressRegion: "CA" # NY
#     postalCode: "94560" # 10019
#     addressCountry: "US" # US

#   review:
#     ratingValue: "4.5" #4.5
#     bestRating: "5" # 5
#     authorName: "Google Review" # Google Review
#     reviewType: "Organization" # Organization. Google Review ->"Organization", 

#   # review:
#   #   ratingValue: "4.5"
#   #   bestRating: "5"
#   #   authorName: "Yelp"
#   #   reviewType: "Organization" # Yelp 是一个组织，因此设置为 Organization

#   # review:
#   #   ratingValue: "4.9"
#   #   bestRating: "5"
#   #   authorName: "John Doe"
#   #   reviewType: "Person"


#   geo:
#     latitude: 37.55052611620485 # 40.761293
#     longitude: -122.0512589463209 # -73.982294
#   url: "https://crabbynewark.com/" # https://www.example.com
 
#   telephone: "+1-510-588-1218" # +1212345678

#   servesCuisine: [
#     "Seafood",
#     "Cajun Cuisine",
#     "American Cuisine"
# ]

#   priceRange: "$$" # $,$$,$$$,$$$$. $->Inexpensive, $$->Moderate, $$$->Expensive, $$$$->Luxury

#   openingHours:
#   - dayOfWeek:
#       - "Monday"
#       - "Tuesday"
#       - "Wednesday"
#       - "Thursday"
#       - "Friday"
#     opens: "11:30"
#     closes: "15:00"
#   - dayOfWeek:
#       - "Monday"
#       - "Tuesday"
#       - "Wednesday"
#       - "Thursday"
#       - "Friday"
#     opens: "17:00"
#     closes: "21:00"
#   - dayOfWeek:
#       - "Saturday"
#       - "Sunday"
#     opens: "12:00"
#     closes: "21:00"
   
#   menu: "https://crabbynewark.com/" # https://example.com/
  
#   # acceptsReservations: true # true or false
#   hasMenu: "https://crabbynewark.com/" # https://crabbynewark.com/full-menu
  
#   starRating:
#     ratingValue: "4.5" # 4.5
#     bestRating: "5" # 5
#     author: "Google Review" # Michelin Guide, Google Review
#     authorType: "organization" #person,organization

#   currenciesAccepted: "USD" # USD
  
#   paymentAccepted: "Cash, Visa"

#   hasMenuSection:
#     - name: "SEAFOOD" # Appetizers
#       image: "https://crabbynewark.com/gallery/Seafood_Whole_Lobster.webp"
#       description: "From the heart of Newark, CA, Crabby Crabby Restaurant is a corner where tradition meets flavor."
#       hasMenuItem:
#         - name: "Half Pound Snow Crab"
#           description: "Succulent half pound of snow crab, expertly prepared for a delightful dining experience."
#           price: "20.50"
#           image: "https://crabbynewark.com/gallery/Seafood_Half_Pound_Snow_Crab.webp"
#         - name: "Whole Lobster"
#           description: "Savor the taste of our whole lobster, cooked to perfection and bursting with flavor."
#           price: "52.99"
#           image: "https://crabbynewark.com/gallery/Seafood_Whole_Lobster.webp"
#     - name: "Combo" # Main Courses
#       hasMenuItem:
#         - name: "Combo Deal #1"
#           description: "1lb Head On Shrimp, 1lb Crawfish Or Clams, 1lb Green Mussels. Pick 2 Free Items:1 Corn Or 2 Potatoes Or 4 Pc of Sausages."
#           price: "45.00"
#           image: ""
#         - name: "Combo Deal #2"
#           description: "1lb King Crab Legs, 1lb Head On Shrimp, 1lb Crawfish Or Clams. Pick 3 Free Items: 1 Corn Or 2 Potatoes Or 4 Pc of Sausages."
#           price: "80.00"
#           image: ""
#     - name: "Lunch Specials" # Appetizers
#       hasMenuItem:
#         - name: "Lunch Special #1"
#           description: "0.5 lb Head On Shrimp, 0.5 lb Black Mussels"
#           price: "12.99"
#           image: ""
#         - name: "Lunch Special #2"
#           description: "0.5 lb Head On Shrimp, 0.5 lb Green Mussels"
#           price: "12.99"
#           image: ""
#     - name: "Fried" # Main Courses
#       # description: "Each Selection Made To Order,Hand-Tossed In Our Secret Batter."
#       image: "https://crabbynewark.com/gallery/Fried_Calamari_W_Fries.webp"
#       hasMenuItem:
#         - name: "Fried Calamari W Fries"
#           description: "Crispy calamari served with golden fries, perfect for sharing or indulging on your own."
#           price: "12.99"
#           image: "https://crabbynewark.com/gallery/Fried_Calamari_W_Fries.webp"
#         # - name: "S1 水煮鱼片 Sichuan Poached Spicy Fish Filet"
#         #   description: "Spicy poached fish fillet in Sichuan style."
#         #   price: "12.99"
#         #   image: ""
        
#   offers:
#     - name: "Lunch Specials"
#       description: "0.5 lb Head On Shrimp, 0.5 lb Black Mussels, 1 corn 2 potatoes 4 pc sausages. Only $12.99. Available Monday to Friday, 11:30 AM to 3 PM."
#       priceCurrency: "USD"
#       price: "12.99"
#       image: "https://crabbynewark.com/offer.png"
#     # - name: "10% off cash discount on family meal takeout"
#     #   description: "Get 10% off when you pay with cash for family meal takeout."
#     #   priceCurrency: "USD"
#     #   price: "varies"
#     #   image: ""
#     # - name: "Family Set: Any 3 dishes for $40"
#     #   description: "Choose any 3 dishes for just $40, includes free rice."
#     #   priceCurrency: "USD"
#     #   price: "40"
#     #   image: ""
#     # - name: "Free rice with lunch"
#     #   description: "Receive free rice with any lunch order."
#     #   priceCurrency: "USD"
#     #   price: "0"
#     #   image: ""

---
<!-- hello world -->