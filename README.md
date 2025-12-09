public class MohammedTerfa
{
    // Constructor
    public MohammedTerfa()
    {
        Name = "Mohammed Terfa";
        Email = "mohammedterfa@gmail.com";

        BackendSkills = new List<string>
        {
            "Laravel / PHP",
            ".NET / C#",
            "API Development"
        };

        FrontendSkills = new List<string>
        {
            "Vue.js",
            "Inertia.js",
            "Livewire",
            "Nuxt.js",
            "JavaScript"
        };

        OtherSkills = new List<string>
        {
            "Database Design",
            "Git & GitHub"
        };
    }

    // Properties
    public string Name { get; }
    public string Email { get; }

    public List<string> BackendSkills { get; }
    public List<string> FrontendSkills { get; }
    public List<string> OtherSkills { get; }

    // Methods
    public string GetSummary()
    {
        return $"{Name}: Software Developer specializing in Laravel, .NET, and modern web technologies.";
    }

    public void WorkApproach()
    {
        /* 
           - Focus on clean, maintainable, and scalable code.
           - Follow engineering principles and good architectural practices.
           - Aim for stable, well-structured systems.
        */
    }

    public void Contact()
    {
        // التواصل عبر الإيميل
        Console.WriteLine($"Email: {Email}");
    }
}
