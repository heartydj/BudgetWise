# 💰 BudgetWise - Complete Budget Tracking Application

## 🎨 Features

### ✨ **Light & Dark Theme**
- Beautiful light and dark modes
- Smooth theme transitions
- Theme preference saved across sessions
- Eye-friendly color schemes

### 🔐 **Authentication System**
- User registration with password strength indicator
- Secure login system
- Session management
- Password validation

### 📊 **Dashboard**
- Real-time financial statistics
- Budget overview
- Expense tracking
- Quick action buttons
- Personalized greetings based on time of day

### 💳 **Expense Management**
- Add expenses with date, category, amount, description
- 8 predefined expense categories with icons
- Budget setting and tracking
- Real-time budget calculations
- Filter expenses (All/Today/This Week)
- Delete individual expenses
- Beautiful responsive table layout

### 📈 **Reports & Analytics**
- Visual pie chart for spending by category
- Line chart showing daily spending trends
- Summary statistics (total spent, average per day, largest expense)
- Category breakdown with transaction counts
- All charts adapt to light/dark theme

### 💡 **Financial Insights**
- Spending score (0-100) with visual indicator
- Budget status alerts (exceeded, approaching limit, on track)
- Top spending category analysis
- Personalized recommendations
- Smart financial tips

## 🚀 How to Use

### 1. **Getting Started**
   - Open `index.html` in your browser
   - Click "Get Started" or navigate to registration

### 2. **Create Account**
   - Enter username (min 3 characters)
   - Enter valid email
   - Create password (min 6 characters)
   - Password strength indicator guides you
   - Confirm password
   - Click "Create Account"

### 3. **Login**
   - Enter your username and password
   - Click "Sign In"
   - You'll be redirected to the dashboard

### 4. **Set Your Budget**
   - Go to "Expenses" page
   - Find "Monthly Budget" section
   - Enter amount (e.g., 50000)
   - Click "Set Budget"

### 5. **Add Expenses**
   - Fill in the expense form:
     - **Date**: When you made the purchase
     - **Category**: Select from 8 categories
     - **Amount**: Enter the cost
     - **Description**: Brief note
   - Click "Add Expense"
   - Expense appears in the table immediately

### 6. **View Reports**
   - Navigate to "Reports" page
   - See pie chart of category distribution
   - View daily spending trend
   - Check category breakdown

### 7. **Get Insights**
   - Go to "Insights" page
   - See your spending score
   - Read personalized recommendations
   - Check budget status

### 8. **Switch Themes**
   - Click the theme toggle button (🌙/☀️) in the navigation
   - Theme preference is saved automatically

## 📁 File Structure

```
BudgetWise/
├── index.html          # Landing page
├── registration.html   # User registration
├── login.html         # User login
├── dashboard.html     # Main dashboard
├── expense.html       # Expense management
├── report.html        # Reports & analytics
├── insights.html      # Financial insights
├── theme.css          # Comprehensive theme styles
├── theme.js           # Theme & utility functions
└── README.md          # This file
```

## 💾 Data Storage

All data is stored locally using `localStorage`:
- User credentials (username, password, email)
- Budget limit
- All expense records
- Theme preference
- Login session

**Note:** Data is browser-specific. Clearing browser data will delete all information.

## 🎨 Themes

### Light Theme
- Clean white backgrounds
- Blue accents (#3b82f6)
- Easy-to-read typography
- Professional appearance

### Dark Theme
- Dark gray backgrounds (#1f2937)
- Lighter blue accents (#60a5fa)
- Reduced eye strain
- Modern aesthetic

## 🔧 Technical Details

### Technologies
- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS variables
- **JavaScript (ES6+)** - Interactive functionality
- **Chart.js** - Data visualizations
- **Google Fonts (Inter)** - Professional typography
- **LocalStorage API** - Client-side persistence

### Key Features
- Fully responsive design
- Smooth animations and transitions
- Toast notifications for user feedback
- Form validation
- Currency formatting
- Date formatting
- Scroll animations
- Theme persistence

### Browser Support
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any modern browser with localStorage support

## 🎯 Usage Examples

### Setting a Budget
```
1. Go to Expenses page
2. Enter ₹50,000 in budget input
3. Click "Set Budget"
4. Budget displayed in real-time
```

### Adding an Expense
```
1. Select today's date
2. Choose "Food" category  
3. Enter ₹500 for amount
4. Add description "Groceries"
5. Click "Add Expense"
6. See budget update automatically
```

### Viewing Reports
```
1. Navigate to Reports
2. See pie chart of spending
3. View daily trend chart
4. Check category breakdown
```

## 🌟 Key Improvements

### From Original Version
1. **Complete Theme System**
   - Light and dark modes
   - Smooth transitions
   - Persistent preferences

2. **Enhanced UI/UX**
   - Modern card layouts
   - Smooth animations
   - Interactive elements
   - Toast notifications
   - Better spacing and typography

3. **Improved Functionality**
   - Better form validation
   - Real-time calculations
   - Date/currency formatting
   - Filter capabilities
   - Comprehensive error handling

4. **Professional Design**
   - Consistent color scheme
   - Beautiful gradients
   - Responsive grid layouts
   - Proper shadows and borders
   - Accessibility considerations

5. **Better Data Management**
   - Utility functions for storage
   - Proper date handling
   - Safe parsing
   - Error recovery

## 🐛 Troubleshooting

**Can't login after registration**
- Ensure exact same username/password
- Check for typos
- Clear browser cache if needed

**Expenses not showing**
- Check selected filter (All/Today/Week)
- Ensure date is correct
- Refresh the page

**Budget not updating**
- Verify budget was set successfully
- Check console for errors
- Refresh and try again

**Theme not switching**
- Ensure JavaScript is enabled
- Check browser compatibility
- Clear cache and reload

**Charts not loading**
- Verify internet connection (Chart.js loads from CDN)
- Check browser console for errors
- Ensure expenses exist

## 🔒 Security Notes

- Passwords stored in localStorage (for demo)
- For production: implement proper backend
- Consider:
  - Password hashing
  - Server-side storage
  - HTTPS protocol
  - Session tokens
  - OAuth integration

## 📱 Mobile Responsive

- Adapts to all screen sizes
- Touch-friendly buttons
- Readable on small screens
- Optimized layouts

## 🎓 Learning Resources

This project demonstrates:
- Modern JavaScript (ES6+)
- CSS Grid & Flexbox
- LocalStorage API
- Chart.js integration
- Responsive design
- Theme system implementation
- Form handling & validation
- Data manipulation

## 📝 Future Enhancements

- Export data to CSV/Excel
- Import bank statements
- Recurring expenses
- Multiple budgets
- Email notifications
- Cloud sync
- Mobile app version
- Backend integration
- Multi-user support

## 🤝 Credits

Built with:
- Chart.js for visualizations
- Google Fonts for typography
- Modern web standards

---

**Made with ❤️ for better financial management**

© 2025 BudgetWise. All rights reserved.
