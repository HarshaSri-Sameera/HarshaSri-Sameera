# I'm darkfire, Sameera <img src="https://media.tenor.com/m1WLq0zS4i0AAAAC/blueorredpill-doesthematrixhaveyou.gif" width="90" height="65"/>

<img src="https://media.tenor.com/SS2WAJxsr2gAAAAM/im-in-matrix.gif" width="340" height="200"/>

```JSX
function Darkfire(props){
  const {
    details: {
      fullName: "Harsha Sri Sameera",
      age: "20",
      education: "Bachelor of Science in Computer Science Engineering"
    },
    skills = [
      "React",
      "TypeScript",  
      "JavaScript",
      "BootStrap",
      "Lua",
      "Git",
      "HTML & CSS",
      "C++",
      "Python",
      "Go",
      "Java",
      "BashScripting"
    ],
    work: {
      company: "Embe Home Automations",  
      position: "Full Stack Engineer"
    },
    goals = [
      "build something cool and useful",
      "to live life as I dreamt of"
    ], 
    weakness = [
      "Stubborn heart"
    ]
    location: {
      city: "Kakinada",
      country: "India"
    }
    Sports: {
      martial arts: "Taekwondo",
      indoor: "Rubick's Cubes"
    }
  } = props;
  
  const {t} = useTranslation();

  return (
    <article className="flex bg-white dark:bg-black text-black dark:text-white rounded p-4 md:p-2 shadow-sm">
      <Avataram />
      <div className="grid gap-2">
        <h1 className="text-lg space-x-2">
          <span>{details.fullName}</span> 
          <span className="text-sm text-gray">{details.age}</span>
        </h1>
        <h4 className="text-md">{details.education}</h4>
	
        <div className="px-4 py-2 border">
          <p>{t('common.work')}: {work.company} as {work.position}</p> 
          <p>{t('common.location')}: {location.city}, {location.country}</p>
	      </div>
	
        <ul className="flex flex-wrap items-center gap-2">
          {skills.map((skill) => (
            <li key={skill} className="p-2 rounded bg-indigo-500 text-white cursor-pointer select-none">
              {skill}
            </li>
          ))}
        </ul>
      </div>
    </article>
  );
};

export default Darkfire;
```
<div align="center">
	![Sameera's GitHub stats](https://github-readme-stats.vercel.app/api?username=HarshaSri-Sameera&show_icons=true&theme=tokyonight) 
</div>
	
<img src="https://camo.githubusercontent.com/3c6c60b27c5b25b5bd818fdbedca1e9d63caa1f0c69f8a9e830c58190f40396b/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f76486b704b7643656d4655436c6a646937622f67697068792e676966" width="340" height="200"/>















<!-- <h5 align="center">Namaste! 🙏<h5>
  
-----------------------------
  
###### About Me
<div align="center">
🎓 Studying Computer Science Engineering at AEC.<br>
🌱 Exploring and absorbing new tech and developing softwares.<br>
😎 Rubicks Cuber ~ Teakwondo Player🥋 ~ Problem Slover ~ Thinker <br>
🔬 Exicted to work in Research and Development fields🤍 <br>
🤩 Interested in Developement and Innovation, full stack web dev. <br>
⚡ Fun fact: well, I'm a super curious person you have ever met.<br> 
</div>

-----------------------------

 ###### Tech Stack
 <div align="center">
 💻 Python | C++ | Java <br>
 🌐 HTML | CSS | JavaScript | TypeScript | Bootstrap | ReactJS ♡ <br>
 🔮 Git | Markdown | BashScripting <br>
 👩‍💻 Windows | macOS | BlackArch Linux (Garuda distro)
 </div>
  
-----------------------------
 -->



