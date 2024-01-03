# I'm darkfire, Sameera         <img src="https://media.tenor.com/m1WLq0zS4i0AAAAC/blueorredpill-doesthematrixhaveyou.gif" width="50" height="40" />
<!-- <img src="https://media.tenor.com/m1WLq0zS4i0AAAAC/blueorredpill-doesthematrixhaveyou.gif" width="30" height="30" /> <img src="https://media.tenor.com/m1WLq0zS4i0AAAAC/blueorredpill-doesthematrixhaveyou.gif" width="30" height="30" /> <img src="https://media.tenor.com/m1WLq0zS4i0AAAAC/blueorredpill-doesthematrixhaveyou.gif" width="30" height="30" /> • • • -->

<img src="https://media.tenor.com/SS2WAJxsr2gAAAAM/im-in-matrix.gif" width="340" height="200"/>

```jsx
function Darkfire(props){
  const {
    details = {
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
    work = {
      company: "Anubudh EdTech",  
      position: "Full Stack Developer"
    },
    goals = [
      "build something cool and useful",
      "to live an adventurous life"
    ], 
    flaw = [
      "Stubborn heart"
    ]
    location = {
      city: "Kakinada",
      country: "India"
    }
    sports = {
      martialArts: "Taekwondo",
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

<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExeDl4NXFlcWV0OTRtNHRwbjY4cXo1aXh4M2wxY3J3Z3ByenE3NmE0bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/vHkpKvCemFUCljdi7b/giphy.gif" width="340" height="200"/>

<div align="center">
	
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=HarshaSri-Sameera&layout=compact&theme=dark#gh-dark-mode-only)](https://github.com/HarshaSri-Sameera/github-readme-stats#gh-dark-mode-only)	
	
![Sameera's GitHub stats](https://github-readme-stats.vercel.app/api?username=HarshaSri-Sameera&show_icons=true&theme=dark) 
	
</div>

---------------------------------------------

###### <sub> A heartfelt shout-out to my amazing friend [Jiya Ull Haq](https://github.com/Jiya-Ull-Haq) for his unwavering support and encouragement throughout my coding journey. Your belief in me has been the driving force behind my growth and success. Together, we're creating something extraordinary. Thank you for being my coding companion and constant inspiration! 🙌 </sub>














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
