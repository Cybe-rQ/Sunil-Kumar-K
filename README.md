<pre>
Hi! im SK 
     ( Sunil kumar K ).
</pre>

<p>
A bachelor student Recently Graduated , in (BCA) Computer Application.
</p>

'''
public class About {

    // Personal Details
    private String name = "Sunil Kumar K";

    // Education Qualification
    private String degree = "Bachelor of Computer Application (BCA)";
    private String college = "Univesity of Madras ( Annai Violet Arts & Science College )";
    private String graduationPeriod = "2020-2023";

    // Social Media
    private String linkedInProfile = "www.linkedin.com/in/sunil-kumar-k030403";
    private String GithubProfile = "https://github.com/Cybe-rQ";

    // Additional Skills
    private String[] frontEndSkills = {"HTML5", "CSS3", "React.js"};
    private String[] backEndSkills = {"Java", "MySQL"};
    private String[] otherSkills = {"Git & Github", "API"};

    // Operating Systems
    private String[] operatingSystems = {"Windows", "Linux"};

    // Display About Information
    public void displayAbout() {
        System.out.println("Name: " + name);
        System.out.println("Education: " + degree + " at " + college + ", Graduated " + graduationPeriod);
        System.out.println("LinkedIn: " + linkedInProfile);
        System.out.println("Github: " + GithubProfile);

        System.out.println("\nSkills:");
        System.out.println("Front End: " + String.join(", ", frontEndSkills));
        System.out.println("Back End: " + String.join(", ", backEndSkills));
        System.out.println("Other: " + String.join(", ", otherSkills));

        System.out.println("\nOperating Systems: " + String.join(", ", operatingSystems));
    }

    // Main method for testing
    public static void main(String[] args) {
        About myDetails = new About();
        myDetails.displayAbout();
    }
}
'''
