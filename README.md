# First Class Senior High School - Student Registration System

A comprehensive web-based student registration system with professional PDF generation capabilities, built with modern web technologies and Firebase integration.

## 🚀 Features

### Student Registration
- **Dynamic Form Interface**: Clean, responsive form with school color scheme (Green & Yellow)
- **Photo Upload**: Passport photo upload with preview functionality
- **Program Selection**: Multiple academic programs with elective subject options
- **Form Validation**: Comprehensive client-side validation
- **Real-time Preview**: Professional PDF preview before submission

### Admin Dashboard
- **Student Management**: View, filter, and manage all registered students
- **Registration Status**: Toggle between registered/unregistered status
- **Photo Downloads**: Download student passport photos directly
- **Advanced Search**: Filter by name, program, and registration status
- **Analytics**: Dashboard with student statistics and program distribution

### PDF Generation
- **Professional Templates**: School-branded PDF documents
- **Complete Data Export**: All student information including photos
- **Print Ready**: Optimized for both digital and print formats
- **Preview Mode**: Visual preview before generating final PDF

### Authentication & Security
- **Admin Authentication**: Secure login system for administrators
- **Firebase Integration**: Real-time database and file storage
- **Data Protection**: Secure handling of student information

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Firebase (Firestore, Storage, Authentication)
- **PDF Generation**: jsPDF library
- **Icons**: Font Awesome 6.4.0
- **Styling**: Custom CSS with CSS Variables

## 📁 Project Structure

```
first-class-shs-registration/
├── index.html                 # Main application file
├── firebase-config.js         # Firebase configuration
├── assets/
│   ├── css/
│   │   └── style.css         # Main stylesheet
│   ├── js/
│   │   ├── app.js           # Main application logic
│   │   ├── firebase.js      # Firebase services
│   │   └── pdf-generator.js # PDF generation utilities
│   └── images/
│       └── school-logo.png  # School branding
└── README.md
```

## 🔧 Setup Instructions

### Prerequisites
- Firebase account with Firestore, Storage, and Authentication enabled
- Modern web browser with JavaScript enabled

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/first-class-shs-registration.git
```

2. Configure Firebase:
   - Create a new Firebase project
   - Enable Firestore, Storage, and Authentication
   - Update Firebase configuration in the code

3. Deploy:
   - Host on any static web hosting service
   - Firebase Hosting recommended for seamless integration

### Firebase Configuration
Replace the Firebase config in the code with your project details:

```javascript
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-project.firebaseapp.com",
  projectId: "your-project-id",
  storageBucket: "your-project.appspot.com",
  messagingSenderId: "your-sender-id",
  appId: "your-app-id"
};
```

## 💡 Usage

### For Students
1. Navigate to the registration form
2. Fill in personal and academic details
3. Upload passport photo
4. Select program and elective subjects
5. Preview and submit registration

### For Administrators
1. Login with admin credentials
2. Access dashboard to view all registrations
3. Filter and search student records
4. Download photos and generate PDF reports
5. Update registration status

## 🎨 Design Features

- **School Branding**: Professional green and yellow color scheme
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Accessibility**: WCAG compliant with proper contrast ratios
- **User Experience**: Intuitive navigation with visual feedback
- **Professional UI**: Clean, modern interface with smooth animations

## 🔒 Security Features

- Admin authentication required for dashboard access
- Secure file uploads with validation
- Protected database operations
- Input sanitization and validation

## 📊 Data Management

- **Firestore**: Student records and metadata
- **Firebase Storage**: Student photos and documents
- **Real-time Updates**: Live data synchronization
- **Backup & Recovery**: Automated Firebase backups

## 🚀 Deployment Options

### Firebase Hosting (Recommended)
```bash
firebase init hosting
firebase deploy
```

### Netlify
- Connect GitHub repository
- Configure build settings
- Deploy automatically

### Traditional Web Hosting
- Upload files to web server
- Configure Firebase security rules
- Set up custom domain if needed

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions:
- Create an issue in the GitHub repository
- Contact the development team
- Check documentation in the wiki

## 🔄 Version History

- **v1.0.0** - Initial release with core registration and admin features
- **v1.1.0** - Added PDF generation and photo download capabilities
- **v1.2.0** - Enhanced UI with school branding and responsive design

## 🌟 Future Enhancements

- [ ] Email notifications for registration confirmations
- [ ] Bulk student import/export functionality
- [ ] Advanced reporting and analytics
- [ ] Mobile app version
- [ ] Multi-language support
- [ ] Integration with school management systems

---

**Built with ❤️ for First Class Senior High School**
