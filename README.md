## Keylogger

This project consists of two scripts, `Zlogger.py` and `keylogger.py`, which work together to capture keystrokes and email the logs at regular intervals.

### Script 1: Zlogger.py

#### Overview
`Zlogger.py` initiates the keylogger by creating an instance of the `Keylogger` class with a specified time interval and email credentials.

#### Usage
1. **Configure Email and Interval**: In `Zlogger.py`, specify the time interval (in seconds) and replace the placeholders `"sample@gmail.com"` and `"password"` with valid credentials:
   ```python
   my_keylogger = keylogger.Keylogger(120, "your_email@example.com", "your_password")
   ```
2. **Run the Script**:
   ```bash
   python Zlogger.py
   ```

### Script 2: keylogger.py

#### Overview
`keylogger.py` defines the `Keylogger` class, which captures keystrokes and sends them to the specified email address at regular intervals.

#### Key Features
- **Keystroke Logging**: Captures all keystrokes typed on the keyboard.
- **Regular Email Reporting**: Sends the recorded keystrokes to a specified email address every set interval.

#### Requirements
- **Python 3.x**
- **Libraries**:
  - `pynput`: Used for capturing keystrokes.
  - `smtplib`: For sending emails.

#### Important Note
This project is for **educational purposes only**. Unauthorized use on any system without explicit consent is prohibited.

### Authors
- [Zaid Sabih](https://ie.linkedin.com/in/zaid-sabih-al-quraishi-5444a6127)
- [Uzoeshi Daniel](https://www.linkedin.com/in/daniel-ikenna-33b709235)
