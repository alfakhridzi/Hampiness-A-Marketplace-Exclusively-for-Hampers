# Hampiness-A-Marketplace-Exclusively-for-Hampers
Hampiness is an information system and mobile app mockup for a marketplace dedicated to hampers. It connects customers with hamper vendors, and gives each side a simpler way to order, manage products, track delivery, and read sales reports.


Problem Analysis

The team used fishbone diagrams to find the root causes behind two problems.

1. Decreasing customer satisfaction
   - No real-time order tracking; unintuitive ordering process
   - Unclear product information (contents, size); few personalization options
   - Stock not updated in real time; delivery estimates not shown accurately
   - Hard to time hamper delivery for a specific occasion; waiting for manual confirmation from admin or vendor

2. Delays in reaching optimal operational efficiency
   - No standard guide for describing hampers, setting prices, or uploading photos; vendor data input not fully digitized
   - Vendor notification system not optimal; add-package form hard to use
   - Inconsistent information quality; unclear app catalog
   - Vendors confused when filling in the package form; slow vendor response to orders

Solution Overview

Hampiness serves three actors:
- Customer, Register and sign in, browse vendors and hamper categories, add packages to a cart, check out with address and delivery time, pay, track order status, and leave reviews
- Vendor, Add products, bundle products into hamper packages, receive new-order notifications, and submit delivery proof (photo and notes)
- Admin, View order trend reports and transaction activity summaries

Order status flow:
Waiting for payment, then Payment successful, then Delivered, then Done. An order moves to Cancelled if payment fails.

System Analysis & Design
- Fishbone Diagram, Root causes of the two problems above
- Context Diagram, The system and its data exchange with Customer, Vendor, and Admin
- DFD Level 0, Six processes: manage account, manage catalog, place order, deliver order, review, and send report data
- Use Case Diagram, Customer: register, place order, give review. Vendor: fill delivery form, add products, add hamper packages. Admin: compile order trend and transaction summary report
- Class Diagram, `Pelanggan`, `Vendor`, `Hampers`, `FormPemesanan`, `DetailFormPemesanan`, `FormPengirimanPaket`, `FormReview`, `FormAddProduct`, `FormAddPackage`
- Sequence Diagrams, Ordering, registration, review, delivery form, add product, add package, and the two admin reports
- State Transition Diagrams, Order, hamper package, and product lifecycles
- Activity Diagrams, Step-by-step flows for registration, ordering, review, delivery form, adding products and packages, and reports

UI Design
The Figma mockup covers the main flows for each actor:

- Customer: Sign up, home with recommended vendors, vendor profile, hamper categories, add to cart, cart, checkout, payment, and order states (waiting, successful, cancelled, delivered)
- Vendor: new-order notification, side menu, order history, delivery proof form, add product, add hamper package
- Admin: order trend report, transaction summary report, and the combined report dashboard output

My Contribution

- Created the Use Case Diagram, Class Diagram, and Activity Diagrams
- Designed the app screens in Figma

