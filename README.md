# Secure Image Vault

A secure mobile application for encrypting and decrypting images using AES or XChaCha20 encryption methods. Built with Flutter for Android.

## Features

- User registration with strong password policy
- Secure login with OTP verification
- Image encryption using AES or XChaCha20
- Image decryption with password protection
- Modern and user-friendly interface
- Secure storage of encrypted images

## Getting Started

### Prerequisites

- Flutter SDK (>=3.0.0)
- Android Studio / VS Code
- Android device or emulator

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/secure-image-vault.git
cd secure-image-vault
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Usage

### Registration
1. Launch the app
2. Tap "Register"
3. Enter your username, email, and password
4. Follow the password requirements:
   - Minimum 8 characters
   - At least one uppercase letter
   - At least one lowercase letter
   - At least one number
   - At least one special character (!@#$%^&*)
5. Verify your email with the OTP sent

### Login
1. Enter your username and password
2. Enter the OTP sent to your email
3. After 3 failed attempts, you'll be locked out for 5 minutes

### Encrypting Images
1. From the home screen, tap "Encrypt Image"
2. Select an encryption method (AES or XChaCha20)
3. Choose an image from your gallery
4. Enter an encryption password
5. Tap "Encrypt"

### Decrypting Images
1. From the home screen, tap "Decrypt Image"
2. Select an encrypted image from the list
3. Enter the decryption password
4. View the decrypted image

## Security Features

- Strong password policy enforcement
- OTP-based authentication
- Account lockout after failed attempts
- Secure storage of encrypted images
- Password visibility toggle
- Real-time password strength meter

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flutter team for the amazing framework
- Crypto package for encryption algorithms
- Image Picker package for image selection
