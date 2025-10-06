# Guadalajara's Electromechanical Braille Printer: Empowering Blind Communities Worldwide Through Mexican Innovation

## About

An open-source electromechanical Braille printer prototype designed to democratize access to written materials for blind students in Mexico. Commercial Braille embossers cost 50,000+ MXN, making them unaffordable for nearly half of Mexico's population living in poverty. This prototype costs under 10,000 MXN while maintaining functionality and reliability.

## Key Features

- **Integrated OCR System**: Uses Tesseract OCR on Raspberry Pi 4B to scan and convert printed Spanish text to Grade 1 Braille
- **Camera-Based Scanning**: Eliminates dependence on pre-digitized content; users can convert any printed material independently
- **Electromechanical Embossing**: Arduino MEGA 2560 controls 3x2 solenoid array for tactile dot formation
- **Accessible Interface**: Tkinter-based GUI designed for screen reader compatibility
- **Low Power Consumption**: Operates at 12-24V (vs. 30-50V in commercial models)

## Technical Stack

- **Processing**: Raspberry Pi 4B (4-8GB RAM)
- **OCR**: Tesseract with configurable LSTM models, DPI optimization (300-1200), threshold tuning
- **Microcontroller**: Arduino MEGA 2560
- **Actuators**: NEMA17 stepper motors, MG995/MG996R servos, relay modules
- **Software**: Python, Arduino C++, Tkinter GUI
- **Hardware Design**: CAD files for 3D-printed/MDF enclosure

## Project Goals

Developed in partnership with the Helen Keller Institution in Guadalajara, this project targets blind students aged 10-18 and aligns with UN Sustainable Development Goals 4 (Quality Education), 8 (Decent Work), and 10 (Reduced Inequalities).

## Current Status

Prototype testing phase (December 2025 - February 2026) with user feedback from blind students in Guadalajara and Zapopan, Jalisco, Mexico.

## Documentation

- Full parts list with Mexican supplier links
- Assembly instructions with photos
- Software installation guide
- Calibration procedures
- Survey templates for user testing

## Limitations

- Grade 1 Braille only (no contractions)
- Spanish language support
- No tactile graphics
- Prototype stage (not certified for mass production)

## Contributing

We welcome contributions from developers, educators, and accessibility advocates. See CONTRIBUTING.md for guidelines on:
- Hardware improvements
- Multi-language support
- Grade 2 Braille implementation
- User interface enhancements
- Documentation translations

## License

MIT License

## Contact

Developed by Johan Corona González, Mauro Axel Félix de los Ríos, and Emiliano García Gutiérrez.

For collaboration inquiries or implementation support: [tu-email@ejemplo.com]

## Acknowledgments

Helen Keller Institution (Guadalajara) for user testing partnership and invaluable feedback from the blind community.

---

**⚠️ Note**: This is an educational prototype. While functional, it requires further development before commercial deployment. Use and modify at your own discretion.
