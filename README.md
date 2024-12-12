# Password Cracking - The Art of Hash Hunting

## Objective

This lab focused on utilizing password cracking techniques using VirtualBox and Kali Linux. By employing tools such as John the Ripper and Hashcat, I explored different methods for cracking password hashes, including brute-force and dictionary attacks. I also leveraged Cewl for gathering email addresses to generate potential usernames. The goal was to understand the practical use of password cracking tools and optimize strategies for efficient hash cracking.

### Skills Learned

- Password Cracking Techniques: Gained experience with brute-force and dictionary attacks using John the Ripper and Hashcat to crack password hashes from shadow and SAM dump files.
- Wordlist Generation and Customization: Used wordlists like "rockyou.txt" and custom wordlists generated with tools like Cewl to optimize the cracking process.
- Hash Identification and Handling: Developed skills in identifying hash types and using the appropriate tools and parameters for cracking, such as specifying hash types (e.g., SHA-512, LM).
- Tool Comparison and Optimization: Gained hands-on knowledge of the differences between CPU-based and GPU-based cracking, comparing the performance of John the Ripper and Hashcat.
- Data Scraping and Username Generation: Learned to scrape websites for email addresses using Cewl and adapt username generators to convert emails into potential usernames for further cracking attempts.

### Tools Used

- John the Ripper: Used for dictionary and brute-force password cracking, including support for SHA-512 with salt and other hash formats.
- Hashcat: Leveraged for GPU-accelerated password cracking, despite using CPU mode due to system limitations, for cracking both shadow and SAM dump files.
- Cewl: Utilized to scrape email addresses from websites, creating custom wordlists for password cracking and assisting in username generation.
- Username Generator (modified): Adapted the username generator tool to work with email addresses scraped by Cewl, producing potential usernames based on email formats.
- VirtualBox/Kali Linux: Set up and configured the virtual machine environment to run password cracking tools and perform experiments.

## Navigating This Repository

- 'Password Cracking - The Art Of Hash Hunting.pdf' is the final report for this project.
