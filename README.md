# active-cronjob-list-generator

**A Bash Script for Generating Active Cron Job Lists**

The active-cronjob-list-generator repository contains a Bash script that generates a list of active cron jobs on a Linux system. The script parses the crontab file and extracts information about scheduled tasks, including their time, user, and command. The script is easy to use, customizable, and cross-platform compatible.

**Features:**

- **Simple and Efficient:** Generates a comprehensive list of active cron jobs with minimal overhead.
- **Customizable Output:** Easily modify the output format to suit your needs.
- **Cross-Platform Compatibility:** Runs on various Linux distributions.

**Usage:**

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:AltusX1/active-cronjob-list-generator.git
   ```
2. **Run the Script:**
   ```bash
   ./active-cronjob-list-generator.sh
    ```
**Example Output:**

   ```bash
   mi   h   d   m   w   user    command
   0    0   *   *   *   root    /usr/sbin/ntpdate pool.ntp.org
   15   10  *   *   1   user1   /path/to/script.sh
   ```
**Customization:**

You can customize the output format by modifying the script's printing logic. For example, you can add headers or change the order of fields.

**License:**

This project is licensed under the MIT License.
