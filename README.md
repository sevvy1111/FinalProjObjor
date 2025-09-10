**Website URL**: https://checkoutph.onrender.com
**Admin Access**: ObjorAdmin pass: admin@123

---

## 🚀 **QUICK START TESTING**

### **5-Minute Core Test**
1. Register account → Search "phone" → Add to cart → Checkout → Message seller

### **15-Minute Full Test**
1. Complete core test → Create listing → Test messaging → Leave review → Test admin

---

## 🛠️ **TESTING SETUP**

### **Test Accounts**
- **Admin**: ObjorAdmin / admin@123
- **Test User 1**: [Create new account]
- **Test User 2**: [Create new account]

### **Test Data**
- **Products**: Create sample listings in different categories
- **Images**: Use provided sample images
- **Locations**: Use different Philippine cities


---

## 🏠 **1. HOMEPAGE & NAVIGATION**

### **Basic Navigation**
- [ ] **Logo and Branding**: CheckoutPH logo displays correctly
- [ ] **Navigation Menu**: All menu items are visible and functional
- [ ] **Responsive Design**: Test on different screen sizes (desktop, tablet, mobile)
- [ ] **Search Bar**: Main search functionality in navigation with real-time suggestions

### **User Authentication Status**
- [ ] **Guest User**: Can view homepage without login
- [ ] **Logged-in User**: Navigation shows user-specific options
- [ ] **Cart Icon**: Shows cart item count badge when items are added
- [ ] **User Profile Menu**: Access to dashboard, profile, orders, and settings

---

## 👤 **2. USER REGISTRATION & AUTHENTICATION**

### **Registration Process**
- [ ] **Sign Up Form**: Complete registration with new email
- [ ] **Form Validation**: Test required fields and validation messages
- [ ] **Profile Creation**: Verify profile is created after registration
- [ ] **Email Verification**: Check if verification process works(no user with same email)
- [ ] **Phone Validation**: Test Philippine mobile number format (10 digits)

### **Login System**
- [ ] **Login Form**: Successfully log in with valid credentials
- [ ] **Invalid Login**: Test with wrong credentials (should show error)
- [ ] **Password Reset**: Test password reset functionality (CONCEPT only)
- [ ] **Logout**: Verify user can log out successfully

### **User Profiles**
- [ ] **Profile View**: Access and view user profile https://checkoutph.onrender.com/accounts/profile/ 
- [ ] **Avatar Upload**: Test profile picture upload functionality with Cloudinary
- [ ] **Profile Editing**: Modify profile information (bio, phone, avatar)
- [ ] **Public Profile**: View other users' profiles
- [ ] **Seller Ratings**: Check seller profile ratings and review system

---

## 🔍 **3. SEARCH & FILTERING SYSTEM**

### **Basic Search**
- [ ] **Text Search**: Search by product title/description
- [ ] **Search Results**: Verify relevant results are displayed (test "phone" "cars" "keyboard")
- [ ] **No Results**: Test search with no matching items
- [ ] **Real-time Suggestions**: Test search suggestions functionality

### **Advanced Filtering**
- [ ] **Price Range**: Filter by minimum and maximum price
- [ ] **Category Filter**: Filter by hierarchical product categories
- [ ] **City/Location**: Filter by geographic location
- [ ] **Distance Filter**: Test location-based filtering (5km, 10km, 25km, 50km, 100km, 500km)
- [ ] **Condition Filter**: Filter by new/used items
- [ ] **Status Filter**: Filter by available/sold items
- [ ] **Sorting Options**: Test sorting by price, date, distance, featured

### **Filter Combinations**
- [ ] **Multiple Filters**: Apply several filters simultaneously
- [ ] **Filter Reset**: Clear all applied filters
- [ ] **Filter Persistence**: Filters remain after page refresh
- [ ] **Location-based Search**: Test distance calculations

---

## 📝 **4. PRODUCT LISTING CREATION & MANAGEMENT**

### **Create Listing Form**
- [ ] **Form Access**: Navigate to "Create Listing" page
- [ ] **Required Fields**: Test all required field validations
- [ ] **Category Selection**: Choose from hierarchical category system
- [ ] **Image Upload**: Upload multiple product images
- [ ] **Location Input**: Enter city and location details
- [ ] **Price & Stock**: Set pricing and inventory quantities
- [ ] **Condition Selection**: Choose between New/Used items
- [ ] **Form Submission**: Successfully create and save listing

### **Listing Management**
- [ ] **My Listings**: View all user's created listings https://checkoutph.onrender.com/accounts/dashboard/ 
- [ ] **Edit Listing**: Modify existing listing details
- [ ] **Delete Listing**: Remove unwanted listings
- [ ] **Status Updates**: Mark items as sold or available
- [ ] **Featured Listings**: Test featured listing functionality (Admin only: https://checkoutph.onrender.com/admin/listings/listing/)
- [ ] **Stock Management**: Verify inventory tracking

---

## 🛒 **5. SHOPPING CART SYSTEM**

### **Adding Items**
- [ ] **Add to Cart**: Add products to shopping cart 
- [ ] **Cart Update**: Verify cart count increases
- [ ] **Stock Validation**: Test adding more than available stock
- [ ] **Multiple Items**: Add different products to cart
- [ ] **Quantity Management**: Change item quantities in cart

### **Cart Management**
- [ ] **View Cart**: Access shopping cart page
- [ ] **Remove Items**: Delete items from cart
- [ ] **Price Calculations**: Verify subtotal and total calculations
- [ ] **Shipping Fee**: Check if shipping costs are applied
- [ ] **Out-of-Stock Detection**: Verify cart validation

### **Cart Persistence**
- [ ] **User Specific**: Cart is tied to logged-in user
- [ ] **Cross-Device**: Test cart on different devices/browsers

---

## 💳 **6. CHECKOUT & ORDER PROCESS(BETA)**

### **Checkout Flow**
- [ ] **Checkout Access**: Proceed from cart to checkout 
- [ ] **Shipping Form**: Fill out delivery information
- [ ] **Order Summary**: Review order details and costs
- [ ] **Credit System**: Apply earned credits through reviews (ObjorAdmin has starting credits)
- [ ] **Payment Method**: Select payment option (COD only)
- [ ] **Order Confirmation**: Complete order placement
- [ ] **Receipt Generation**: View order receipt and invoice

### **Order Management**
- [ ] **Order History**: View all user orders
- [ ] **Order Details**: Access specific order information
- [ ] **Order Status**: Check order status updates (pending, shipped, delivered, cancelled)
- [ ] **Seller Orders**: View orders as a seller
- [ ] **Status Updates**: Update order status as seller
- [ ] **Shipping Address Management**: Test saved addresses functionality

---

## ❤️ **7. WISHLIST SYSTEM**

### **Wishlist Management**
- [ ] **Save Items**: Add items to wishlist
- [ ] **Wishlist Access**: View saved items from profile and bot
- [ ] **Remove Items**: Remove items from wishlist
- [ ] **Wishlist Persistence**: Items remain saved across sessions

---

## 💬 **8. REAL-TIME MESSAGING SYSTEM**

### **Conversation Management**
- [ ] **Start Conversation**: Initiate chat with seller/buyer
- [ ] **Inbox Access**: View all conversations
- [ ] **Message Threads**: Navigate between different chats
- [ ] **Conversation List**: See all active conversations
- [ ] **WebSocket Connection**: Test real-time messaging

### **Messaging Features**
- [ ] **Send Messages**: Type and send text messages
- [ ] **Image Sharing**: Upload and send images in chat
- [ ] **Real-time Updates**: Check if messages appear instantly
- [ ] **Read Status**: Verify message read indicators
- [ ] **Unread Count**: Check unread message notifications
- [ ] **Conversation Persistence**: Verify message history

---

## ⭐ **9. RATING & REVIEW SYSTEM(BETA)**

### **Review Creation**
- [ ] **Leave Review**: Rate and comment on purchased items (Status must be "Delivered")
- [ ] **Rating Scale**: Test 1-5 star rating system
- [ ] **Review Validation**: Ensure only buyers can review
- [ ] **Review Display**: Show reviews on product pages
- [ ] **One Review Per Order**: Verify review uniqueness

### **Rating Calculations**
- [ ] **Average Ratings**: Verify rating calculations
- [ ] **Seller Ratings**: Check seller profile ratings

---

## 🔔 **10. NOTIFICATIONS & REAL-TIME FEATURES**

### **Notification System**
- [ ] **Message Alerts**: New message notifications
- [ ] **Order Updates**: Order status change notifications
- [ ] **Review Alerts**: New review notifications
- [ ] **Real-time Delivery**: WebSocket notification system
- [ ] **Notification Management**: Mark as read, view all notifications

### **Sound Effects**
- [ ] **Audio Feedback**: Typing sounds, message alerts, badge updates
- [ ] **Volume Control**: User preferences for sound settings
- [ ] **Cross-Platform**: Test on desktop and mobile devices

---

## 🛡️ **11. SECURITY & VALIDATION**

### **Security Features**
- [ ] **Access Control**: Guest restrictions, user permissions, admin access
- [ ] **Data Protection**: Input sanitization, file upload security
- [ ] **Form Security**: CSRF protection, SQL injection prevention
- [ ] **Phone Validation**: Philippine mobile number format (10 digits)

---

## 📱 **12. RESPONSIVE DESIGN**

### **Mobile & Desktop Experience**
- [ ] **Mobile Navigation**: Touch-friendly interface, mobile menu
- [ ] **Form Usability**: Test forms on different screen sizes
- [ ] **Image Responsiveness**: Check image scaling across devices
- [ ] **Search Functionality**: Test search on mobile and desktop

---

## 🔧 **13. ADMIN & BUSINESS LOGIC**

### **Admin Functions**
- [ ] **Admin Panel**: Access Django admin interface
- [ ] **User Management**: View and manage user accounts
- [ ] **Content Moderation**: User bans, report handling, appeals

### **Business Logic**
- [ ] **Inventory Management**: Stock tracking, out-of-stock handling
- [ ] **Order Processing**: Complete order lifecycle, status transitions
- [ ] **Credit System**: Test credit earning and spending
- [ ] **Data Integrity**: Verify data consistency across operations

---

## 🤖 **14. SUPPORT & REPORTING**

### **Bot Support**
- [ ] **Support Chat**: Access support chat interface
- [ ] **Order Tracking**: Test order status queries through bot
- [ ] **Product Search**: Test product search through bot

### **Reporting System For Admin/Staff**
- [ ] **User Reports**: Create and manage user reports
- [ ] **Report Categories**: Test different report types
- [ ] **Image Evidence**: Upload images with reports
- [ ] **Staff Dashboard**: Access moderation tools (https://checkoutph.onrender.com/reports/staff)

---




