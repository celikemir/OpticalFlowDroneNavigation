# Optical Flow Drone Navigation

A professional iOS application that uses optical flow technology for precise drone navigation and speed estimation.

## Features

- **Real-time Optical Flow Analysis**
  - Good Features to Track algorithm
  - Grid-based flow analysis
  - Real-time vector visualization
  - Depth-aware speed estimation

- **Multiple Operation Modes**
  - Features Mode: Tracks distinct features in the scene
  - Grid Mode: Analyzes flow in a grid pattern
  - MAVLink Mode: Drone communication integration

- **Advanced Speed Estimation**
  - GPS speed integration
  - Optical flow-based speed calculation
  - Depth sensor integration for accurate measurements
  - Real-time speed display

- **Professional UI/UX**
  - Dark mode interface
  - Real-time flow vector visualization
  - Interactive debug view
  - MAVLink status monitoring

## Requirements

- iOS 15.0+
- Xcode 13.0+
- Swift 5.5+
- iPhone with LiDAR sensor (for depth data)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/celikemir/OpticalFlowDroneNavigation.git
```

2. Open `OpticalFlowCV.xcodeproj` in Xcode
3. Build and run the project

## Usage

1. Launch the app
2. Grant camera and location permissions when prompted
3. Select your preferred mode:
   - Features: For tracking distinct points
   - Grid: For uniform flow analysis
   - MAVLink: For drone communication

4. Use the interface controls to:
   - Toggle flow vector visualization
   - View speed analysis
   - Monitor MAVLink status

## Support

### How to Get Help
If you need assistance with the app, please:

1. **Check Common Issues**
   - Camera not working: Make sure you've granted camera permissions
   - Speed not showing: Ensure location services are enabled
   - MAVLink connection issues: Verify your drone is in range

2. **Report Problems**
   - Open a new issue on GitHub
   - Include your device model and iOS version
   - Describe what you were doing when the problem occurred
   - Add screenshots if possible


### Bug Reports
If you encounter any issues, please:
1. Check the [Issues](https://github.com/celikemir/OpticalFlowDroneNavigation/issues) section
2. Create a new issue with:
   - Detailed description of the problem
   - Steps to reproduce
   - Device information
   - iOS version
   - Screenshots if applicable

### Feature Requests
We welcome feature suggestions! Please:
1. Check existing issues to avoid duplicates
2. Create a new issue with the "enhancement" label
3. Provide a clear description of the requested feature

### Contact
For direct support or inquiries:
- LinkedIn: https://www.linkedin.com/in/emirhancelik/

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenCV for iOS
- MAVLink protocol
- Apple's AVFoundation framework
- CoreLocation framework

## Privacy

This app:
- Requires camera access for optical flow analysis
- Requires location access for GPS speed
- Does not collect or store personal data
- All processing is done locally on device

## Version History

- 1.0.0
  - Initial release
  - Basic optical flow implementation
  - MAVLink integration
  - Speed estimation features
