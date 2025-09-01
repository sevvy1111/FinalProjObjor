**Website URL**: https://checkoutph.onrender.com
**Admin Access**: ObjorAdmin pass: admin@123

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
- [ ] **Email Verification**: Check if verification process works
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

## 📝 **3. PRODUCT LISTING CREATION & MANAGEMENT**

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
- [ ] **Featured Listings**: Test featured listing functionality(Must be admin to set a product to featured @https://checkoutph.onrender.com/admin/listings/listing/ )
- [ ] **Test by creating a new listing**: Featured first before newest.
- [ ] **Stock Management**: Verify inventory tracking @dashboard

---

## 🔍 **4. SEARCH & FILTERING SYSTEM**

### **Basic Search**
- [ ] **Text Search**: Search by product title/description
- [ ] **Search Results**: Verify relevant results are displayed (test "phone" "cars" "keyboard"
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

## 💬 **7. REAL-TIME MESSAGING SYSTEM**

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

## ⭐ **8. RATING & REVIEW SYSTEM(BETA)**

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

## 🔔 **9. REAL-TIME NOTIFICATION SYSTEM**

### **Notification Types**
- [ ] **Message Notifications**: New message alerts
- [ ] **Order Updates**: Order status change notifications
- [ ] **Review Notifications**: New review alerts
- [ ] **Reports Notifications**: Reports Status notifications
- [ ] **WebSocket Notifications**: Real-time notification delivery

### **Notification Management**
- [ ] **Notification Count**: Badge shows unread count
- [ ] **Mark as Read**: Click to mark notifications read
- [ ] **Notification List**: View all notifications
- [ ] **Real-time Updates**: Check if notifications appear instantly

---

## 🛡️ **10. SECURITY & PERMISSIONS**

### **Access Control**
- [ ] **Guest Restrictions**: Verify guest user limitations
- [ ] **User Permissions**: Test user-specific access rights
- [ ] **Admin Access**: Verify admin-only features
- [ ] **CSRF Protection**: Test form submission security
- [ ] **Ban System**: Test user suspension functionality

### **Data Validation**
- [ ] **Input Sanitization**: Test with malicious input
- [ ] **File Upload Security**: Verify image upload restrictions
- [ ] **SQL Injection**: Test search and form inputs
- [ ] **XSS Prevention**: Check for script injection attempts
- [ ] **Phone Number Validation**: Test Philippine mobile format

---

## 📱 **11. RESPONSIVE DESIGN & UX**

### **Mobile Experience**
- [ ] **Mobile Navigation**: Test mobile menu functionality
- [ ] **Touch Interactions**: Verify touch-friendly interface
- [ ] **Mobile Forms**: Test form usability on small screens
- [ ] **Image Scaling**: Check image responsiveness
- [ ] **Mobile Search**: Test search functionality on mobile


---

## 🔧 **12. ADMIN & MODERATION FUNCTIONALITY**

### **Admin Panel Access**
- [ ] **Admin Login**: Access Django admin interface
- [ ] **User Management**: View and manage user accounts

### **Content Management** https://checkoutph.onrender.com/reports/staff
- [ ] **User Bans**: Test user suspension functionality
- [ ] **Report Handling**: Process user reports
- [ ] **Ban Appeals**: Test appeal system

---

## 📊 **13. BUSINESS LOGIC**


### **Business Logic**
- [ ] **Stock Management**: Test inventory tracking
- [ ] **Order Processing**: Verify order workflow

---

## 🤖 **14. SUPPORT CHAT(BETA)**

### **Support System**
- [ ] **Support Chat**: Access support chat interface
- [ ] **Bot Responses**: Test Pre-loaded responses
- [ ] **Order Tracking**: Test order status queries
- [ ] **Product Search**: Test product search through bot
- [ ] **Wishlist Access**: Test wishlist functionality through bot

---

## 📋 **15. REPORTING & MODERATION**

### **User Reporting**
- [ ] **Report Creation**: Create user reports
- [ ] **Report Categories**: Test different report types
- [ ] **Image Evidence**: Upload images with reports
- [ ] **Report Status**: Track report progress
- [ ] **Priority System**: Test priority levels

### **Staff Dashboard**
- [ ] **Staff Access**: Access staff moderation tools
- [ ] **Report Management**: Process user reports
- [ ] **User Bans**: Manage user suspensions
- [ ] **Listing Moderation**: Remove inappropriate listings
- [ ] **Appeal System**: Handle ban appeals


---

## 📝 **16. ADDITIONAL FEATURES**

### **Wishlist System**
- [ ] **Save Items**: Add items to wishlist
- [ ] **Wishlist Management**: View and manage saved items
- [ ] **Remove Items**: Remove items from wishlist
- [ ] **Wishlist Access**: Access through profile and bot


