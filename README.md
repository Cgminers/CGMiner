

# CGMiner

**CGMiner** is a highly optimized and configurable multi-threaded ASIC and FPGA miner for cryptocurrencies using the SHA-256 algorithm, such as Bitcoin. Designed for maximum performance and flexibility, CGMiner provides detailed monitoring, remote access, and robust pool support.

## 🚀 Features

- Support for a wide range of ASIC and FPGA hardware (e.g., Antminer, Avalon, Bitmain)
- Stratum and getwork protocol support
- Real-time performance monitoring in the terminal
- Fan and temperature control (if supported by device)
- Extensive command-line configuration options
- API access for remote monitoring and control

## 🖥️ Requirements

- Linux or Windows OS
- USB support for ASIC devices
- Dependencies:
  - `libcurl`
  - `libudev`
  - `libjansson`
  - `libusb`
  - `openssl`
  - `autotools` (for building from source)




### Common Parameters

- `-o` : Pool URL
- `-u` : Worker username
- `-p` : Worker password
- `--api-listen` : Enable API access
- `--api-allow W:127.0.0.1` : Allow API access from localhost
- `--log-file cgminer.log` : Output logs to file

## 📊 Monitoring

CGMiner provides live terminal stats including:
- Hashrate (per device and total)
- Hardware errors
- Temperature monitoring
- Fan speed
- Rejected shares

Remote monitoring via API is also available.

## 🧠 Notes

- USB ASIC devices may require specific udev rules.
- Be sure to use the correct drivers for your mining hardware.
- Always use trusted versions from the [official repository](https://github.com/ckolivas/cgminer).


