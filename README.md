# <img src="https://raw.githubusercontent.com/andresvenegasr/andresvenegasr/master/favicon.ico" align="left" height="56" width="56" > Hi! my name is Andrés Venegas 🐺

### Backend and frontend developer 💻

I'm a Telematics enginner from Querétaro, México and professional software developer for more than 5 years. Currently I work as .NET Developer for ITP Aero. Most of my free time I improve my dev skills learning new back and front technologies.

Follow me: [@venegasdev](https://twitter.com/venegasdev)
Contact me: [contacto@venegas.dev](mailto:contacto@venegas.dev)

```CSharp
using System.Collections.Generic;

namespace Venegas.Developer
{
    public class AndresVenegasRuiz : IProgrammer
    {
        private readonly ILogger<AndresVenegasRuiz> _logger;
        private readonly string name = "Andrés Venegas Ruiz";
        private readonly int age = 25;
        private readonly string email = "contacto@venegas.dev";
        
        public AndresVenegasRuiz(IUserService userService)
        {
            _logger = logger
                ?? throw new ArgumentNullException(nameof(logger));
        }

        public void ContactMe(){
            _logger.Debug(" Write me to: contacto@venegas.dev ");
        }

        public void SocialNetworks(){
            _logger.Debug(" Follow Me in Twitter: @venegasdev. ");
        }

        public IEnumerable<string> Hobbies(){
            var hobbies = new List<string>(){
               "Write code", "Play videogames", "Watch horror movies"
            };

            foreach (var hobby in hobbies)
            {
                _logger.Debug($"I love {hobby}");
            }

            return hobbies;
        }

        public IEnumerable<string> ProgrammingLanguages(){
            var languages = new List<string>(){
                "C#", "TypeScript", "Javascript", "VB", "PHP", "Kotlin", "Swift"
            };

            foreach (var language in languages)
            {
                _logger.Debug($"I work with {language}");
            }

            return Languages;
        }
    }


    public interface IProgrammer{
        void ContactMe();
        void SocialNetworks();
        IEnumerable<string> Hobbies();
        IEnumerable<string> ProgrammingLanguages();
    }
}
```



<!--
**andresvenegasr/andresvenegasr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
