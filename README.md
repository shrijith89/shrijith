```java
public class AboutMe {
    public static void main(String[] args) {
        Shrijith profile = new Shrijith();
        profile.displayProfile();
    }
}

class Shrijith {
    void displayProfile() {
        printBanner("Shrijith PS");
        printSection("Experience", "3+ years in Software Testing; Automation & Manual Testing; WebdriverIO | Cypress | Playwright");
        
        printSection("About Me", 
            "🔭 Currently working as Test Engineer",
            "🤝 Currently learning Playwright",
            "💬 Ask me about Automation Testing",
            "⚡ Reach me at shrijithps89@gmail.com"
        );

        printSection("Connect with me",
            "LinkedIn: https://linkedin.com/in/shrijithps",
            "LeetCode: https://www.leetcode.com/shrijith98"
        );

        printSection("Languages", "JavaScript, Java, Python, C++");

        printSection("Tools",
            "WebdriverIO, Cypress, Playwright, Selenium, Cucumber, Postman, JMeter, Git, JIRA"
        );
    }
}
