# MAKCM 2024
**Open Source ESP32-S3 MAKCM (Kmbox Alternative)**

![MAKCM 2024 Image](https://github.com/user-attachments/assets/02ddc456-4abc-4676-8121-7f3084370923)

Welcome to the MAKCM 2024 project! This is a new open-source implementation for remote injection of mouse control with passthrough, featuring dual ESP32-S3 microcontrollers based on RTOS and advanced task management over the traditional loop.

## Key Features

- **High-Speed Communication**: Supports 6Mbps com port communication speed for seamless performance.
- **Dual ESP32-S3 MCUs**: Utilizing two microcontrollers for enhanced processing power and efficiency.
- **RTOS-Based Task Management**: Using real-time operating system (RTOS) tasks over the conventional loop for better multitasking and system management.
- **Automatic HID Report Descriptor Parsing**: No need for custom firmware; the system automatically parses HID report descriptors.
- **Future-Proof**: The roadmap includes additional features such as controller support, eliminating the need for XIM.
- **Internal PHY in OTG Mode**: !Requires efuse burn!, ensuring the device no longer appears as anything other than device on boot.
- **Ample Storage**: 
  - 4MB Quad SPI Flash per MCU
  - 2MB PSRAM per MCU
- **JSON Streaming for USB Descriptors**: All USB descriptors are easily accessible and followable via JSON streaming.
- **Clean Codebase**: Built with a focus on maintainability and readability.

## Roadmap

- Add comprehensive controller support.
- Expand HID compatibility and features.
- Continue to optimize the RTOS tasks for more efficient use.
- Implement additional security measures.

## Community and Support

Join our [Discord community](https://discord.gg/6TJBVtdZbq) to engage with other developers, share your experiences, and get support from the community.

We are excited to have you on board and look forward to your contributions!

---

Feel free to contribute, raise issues, or suggest enhancements. Together, we can make MAKCM 2024 a robust and versatile tool for everyone.

## Contributing

Please refer to the [Contributing Guidelines](CONTRIBUTING.md) to get started. Contributions are always welcome!

## License

This project is licensed under the [MIT License](LICENSE).

