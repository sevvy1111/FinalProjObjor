# FinalProjObjor
# 🔍 **CheckoutPH**

**Website URL**: https://checkoutph.onrender.com
**Admin Access**: ObjorAdmin pass:admin@123

---

## 🏠 **1. HOMEPAGE & NAVIGATION**

### **Basic Navigation**
- [ ] **Logo and Branding**: CheckoutPH logo displays correctly
- [ ] **Navigation Menu**: All menu items are visible and functional
- [ ] **Responsive Design**: Test on different screen sizes (desktop, tablet, mobile)
- [ ] **Search Bar**: Main search functionality in navigation

### **User Authentication Status**
- [ ] **Guest User**: Can view homepage without login
- [ ] **Logged-in User**: Navigation shows user-specific options
- [ ] **Cart Icon**: Shows cart item count badge when items are added

---

## 👤 **2. USER REGISTRATION & AUTHENTICATION**

### **Registration Process**
- [ ] **Sign Up Form**: Complete registration with new email
- [ ] **Form Validation**: Test required fields and validation messages
- [ ] **Profile Creation**: Verify profile is created after registration

### **Login System**
- [ ] **Login Form**: Successfully log in with valid credentials
- [ ] **Invalid Login**: Test with wrong credentials (should show error)
- [ ] **Password Reset**: Test password reset functionality(BETA/CONCEPT since we had trouble implementing 0auth gmail api)
- [ ] **Logout**: Verify user can log out successfully

### **User Profiles**
- [ ] **Profile View**: Access and view user profile
- [ ] **Avatar Upload**: Test profile picture upload functionality
- [ ] **Profile Editing**: Modify profile information
- [ ] **Phone Validation**: Test phone number format validation

---

## 📝 **3. PRODUCT LISTING CREATION**

### **Create Listing Form**
- [ ] **Form Access**: Navigate to "Create Listing" page
- [ ] **Required Fields**: Test all required field validations
- [ ] **Category Selection**: Choose from hierarchical category system
- [ ] **Image Upload**: Upload multiple product images
- [ ] **Location Input**: Enter city and location details
- [ ] **Price & Stock**: Set pricing and inventory quantities
- [ ] **Form Submission**: Successfully create and save listing

### **Listing Management**
- [ ] **My Listings**: View all user's created listings
- [ ] **Edit Listing**: Modify existing listing details
- [ ] **Delete Listing**: Remove unwanted listings
- [ ] **Status Updates**: Mark items as sold

---

## 🔍 **4. SEARCH & FILTERING SYSTEM**

### **Basic Search**
- [ ] **Text Search**: Search by product title/description
- [ ] **Search Results**: Verify relevant results are displayed
- [ ] **No Results**: Test search with no matching items
- [ ] **Search Suggestions**: Check if autocomplete works

### **Advanced Filtering**
- [ ] **Price Range**: Filter by minimum and maximum price
- [ ] **Category Filter**: Filter by product categories
- [ ] **City/Location**: Filter by geographic location
- [ ] **Distance Filter**: Test location-based filtering

### **Filter Combinations**
- [ ] **Multiple Filters**: Apply several filters simultaneously
- [ ] **Filter Reset**: Clear all applied filters
- [ ] **Filter Persistence**: Filters remain after page refresh

---

## �� **5. SHOPPING CART SYSTEM(BETA)**

### **Adding Items**
- [ ] **Add to Cart**: Add products to shopping cart
- [ ] **Cart Update**: Verify cart count increases
- [ ] **Stock Validation**: Test adding more than available stock
- [ ] **Multiple Items**: Add different products to cart

### **Cart Management**
- [ ] **View Cart**: Access shopping cart page
- [ ] **Quantity Updates**: Change item quantities
- [ ] **Remove Items**: Delete items from cart
- [ ] **Price Calculations**: Verify subtotal and total calculations
- [ ] **Shipping Fee**: Check if shipping costs are applied

### **Cart Persistence**
- [ ] **Session Storage**: Cart items persist during session
- [ ] **User Specific**: Cart is tied to logged-in user

---

## 💳 **6. CHECKOUT & ORDER PROCESS(BETA)**

### **Checkout Flow**
- [ ] **Checkout Access**: Proceed from cart to checkout
- [ ] **Shipping Form**: Fill out delivery information
- [ ] **Order Summary**: Review order details and costs
- [ ] **Apply Credits**: Credits are earned through reviews (ObjorAdmin is set with a starting credits for test)
- [ ] **Payment Method**: Select payment option (COD)
- [ ] **Order Confirmation**: Complete order placement

### **Order Management**
- [ ] **Order History**: View all user orders
- [ ] **Order Details**: Access specific order information
- [ ] **Order Status**: Check order status updates
- [ ] **Receipt/Invoice**: Generate order documentation

---

## 💬 **7. MESSAGING SYSTEM**

### **Conversation Management**
- [ ] **Start Conversation**: Initiate chat with seller/buyer
- [ ] **Inbox Access**: View all conversations
- [ ] **Message Threads**: Navigate between different chats
- [ ] **Conversation List**: See all active conversations

### **Messaging Features**
- [ ] **Send Messages**: Type and send text messages
- [ ] **Image Sharing**: Upload and send images in chat
- [ ] **Real-time Updates**: Check if messages appear instantly(WebSockets were only implemented on ConversationDetail)
- [ ] **Read Status**: Verify message read indicators
- [ ] **Unread Count**: Check unread message notifications

---

## ⭐ **8. RATING & REVIEW SYSTEM**

### **Review Creation**
- [ ] **Leave Review**: Rate and comment on purchased items(Status of order should be "Delivered")
- [ ] **Rating Scale**: Test 1-5 star rating system
- [ ] **Review Validation**: Ensure only buyers can review
- [ ] **Review Display**: Show reviews on product pages

### **Rating Calculations**
- [ ] **Average Ratings**: Verify rating calculations
- [ ] **Seller Ratings**: Check seller profile ratings(existing ref. https://checkoutph.onrender.com/accounts/user/Celvin)

---

## 🔔 **9. NOTIFICATION SYSTEM**

### **Notification Types**
- [ ] **Order Updates**: Order status change notifications(BETA)
- [ ] **Review Notifications**: New review alerts
- [ ] **System Notifications**: General platform updates(Submitted Reports/Appeals)

### **Notification Management**
- [ ] **Notification Count**: Badge shows unread count
- [ ] **Mark as Read**: Click to mark notifications read
- [ ] **Notification List**: View all notifications

---

## 🛡️ **10. SECURITY & PERMISSIONS**

### **Access Control**
- [ ] **Guest Restrictions**: Verify guest user limitations
- [ ] **User Permissions**: Test user-specific access rights(Staff Dashboard on Profile DropDown)
- [ ] **Admin Access**: Verify admin-only features
- [ ] **CSRF Protection**: Test form submission security

### **Data Validation**
- [ ] **Input Sanitization**: Test with malicious input
- [ ] **File Upload Security**: Verify image upload restrictions
- [ ] **SQL Injection**: Test search and form inputs
- [ ] **XSS Prevention**: Check for script injection attempts

---

## 📱 **11. RESPONSIVE DESIGN & UX**

### **Mobile Experience**
- [ ] **Mobile Navigation**: Test mobile menu functionality
- [ ] **Touch Interactions**: Verify touch-friendly interface
- [ ] **Mobile Forms**: Test form usability on small screens
- [ ] **Image Scaling**: Check image responsiveness


---

## ⚡ **12. PERFORMANCE & OPTIMIZATION**


### **User Experience**
- [ ] **Smooth Navigation**: Test page transitions
- [ ] **Error Handling**: Verify graceful error messages
- [ ] **Form Feedback**: Test form submission feedback

---

## 🔧 **13. ADMIN FUNCTIONALITY**

### **Admin Panel Access**
- [ ] **Admin Login**: Access Django admin interface
- [ ] **User Management**: View and manage user accounts
- [ ] **Content Moderation**: Moderate listings and reviews
- [ ] **System Reports**: Access platform analytics

### **Content Management**
- [ ] **User Bans**: Test user suspension functionality
- [ ] **Report Handling**: Process user reports for staff/admin (checkoutph.onrender.com/reports/staff/) or Staff Dashoard

---

## 📊 **14. DATA INTEGRITY**


### **Business Logic**
- [ ] **Stock Management**: Test inventory tracking 
- [ ] **Order Processing**: Verify order workflow
- [ ] **Location Services**: Verify geographic features

---
