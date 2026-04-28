<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Abdelrahman Mohamed — DevOps Engineer</title>
<style>
@keyframes fadeInDown{from{opacity:0;transform:translateY(-20px)}to{opacity:1;transform:translateY(0)}}
@keyframes fadeInUp{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:translateY(0)}}
@keyframes wave{0%,100%{transform:rotate(0deg)}25%{transform:rotate(20deg)}75%{transform:rotate(-10deg)}}
@keyframes gradShift{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
@keyframes iconPop{0%{opacity:0;transform:scale(0.5) translateY(10px)}100%{opacity:1;transform:scale(1) translateY(0)}}

*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:sans-serif;background:#0d1117;color:#e6edf3;padding:2rem 1rem;}

.profile{max-width:700px;margin:0 auto;}

.hero{text-align:center;margin-bottom:2rem;animation:fadeInDown 0.7s ease both;}
.wave-emoji{display:inline-block;animation:wave 1.5s ease-in-out infinite;transform-origin:70% 70%;}
.hero-name{font-size:22px;font-weight:500;margin:0 0 6px;}
.hero-title{font-size:14px;background:linear-gradient(90deg,#534AB7,#1D9E75,#534AB7);background-size:200% auto;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:gradShift 3s ease infinite;}

.section{margin-bottom:1.75rem;animation:fadeInUp 0.6s ease both;}
.section-title{font-size:12px;font-weight:500;color:#8b949e;text-transform:uppercase;letter-spacing:0.08em;margin:0 0 0.75rem;display:flex;align-items:center;gap:6px;}
.section-title::after{content:'';flex:1;height:0.5px;background:rgba(255,255,255,0.1);}

.icon-grid{display:flex;flex-wrap:wrap;gap:10px;}
.icon-chip{display:flex;align-items:center;gap:8px;padding:7px 12px;background:#161b22;border:0.5px solid rgba(255,255,255,0.1);border-radius:8px;cursor:default;transition:border-color 0.2s,transform 0.2s,background 0.2s;animation:iconPop 0.4s ease both;}
.icon-chip:hover{border-color:rgba(83,74,183,0.6);background:#1c2433;transform:translateY(-3px);}
.icon-chip img{width:22px;height:22px;display:block;}
.icon-chip span{font-size:13px;color:#8b949e;white-space:nowrap;}
.icon-chip:hover span{color:#e6edf3;}

.about-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:8px;}
.about-item{display:flex;align-items:flex-start;gap:8px;padding:10px 12px;background:#161b22;border:0.5px solid rgba(255,255,255,0.1);border-radius:8px;font-size:13px;color:#8b949e;line-height:1.4;transition:border-color 0.2s;}
.about-item:hover{border-color:rgba(29,158,117,0.4);}
.about-dot{width:6px;height:6px;border-radius:50%;background:#534AB7;flex-shrink:0;margin-top:5px;}

.stats-row{display:flex;flex-wrap:wrap;gap:10px;}
.stat-img{border-radius:8px;max-width:100%;height:auto;display:block;border:0.5px solid rgba(255,255,255,0.1);flex:1;min-width:220px;}

.links-row{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;}
.link-btn{display:flex;align-items:center;gap:6px;padding:8px 16px;border-radius:8px;font-size:13px;font-weight:500;text-decoration:none;border:0.5px solid rgba(255,255,255,0.1);background:#161b22;color:#e6edf3;transition:transform 0.2s,border-color 0.2s,background 0.2s;}
.link-btn:hover{transform:translateY(-2px);}
.link-btn.gmail:hover{border-color:#E24B4A;background:rgba(226,75,74,0.1);}
.link-btn.whatsapp:hover{border-color:#1D9E75;background:rgba(29,158,117,0.1);}
.link-btn.linkedin:hover{border-color:#378ADD;background:rgba(55,138,221,0.1);}
.link-btn.github:hover{border-color:#888780;background:rgba(136,135,128,0.1);}
.link-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;}
</style>
</head>
<body>
<div class="profile">

  <div class="hero">
    <p class="hero-name"><span class="wave-emoji">👋</span> Hi! I'm Abdelrahman Mohamed</p>
    <p class="hero-title">DevOps Engineer · CI/CD · Cloud · Infrastructure</p>
  </div>

  <div class="section" style="animation-delay:0.1s">
    <p class="section-title">DevOps Tech Stack</p>
    <div class="icon-grid" id="devops-grid"></div>
  </div>

  <div class="section" style="animation-delay:0.2s">
    <p class="section-title">Programming Languages</p>
    <div class="icon-grid" id="lang-grid"></div>
  </div>

  <div class="section" style="animation-delay:0.3s">
    <p class="section-title">About Me</p>
    <div class="about-grid" id="about-grid"></div>
  </div>

  <div class="section" style="animation-delay:0.4s">
    <p class="section-title">GitHub Stats</p>
    <div class="stats-row">
      <img class="stat-img" src="https://github-readme-stats.vercel.app/api?username=Abdelrahman1432000&show_icons=true&theme=dark" />
      <img class="stat-img" src="https://github-readme-streak-stats.herokuapp.com/?user=Abdelrahman1432000&theme=dark" />
    </div>
  </div>

  <div class="section" style="animation-delay:0.5s">
    <p class="section-title">Let's Connect</p>
    <div class="links-row">
      <a class="link-btn gmail" href="mailto:abdulrahman.mohamed.sh@gmail.com">
        <span class="link-dot" style="background:#E24B4A;"></span>Gmail
      </a>
      <a class="link-btn whatsapp" href="https://wa.me/201032737045">
        <span class="link-dot" style="background:#1D9E75;"></span>WhatsApp
      </a>
      <a class="link-btn linkedin" href="https://www.linkedin.com/in/abdelrahman-mohamed-0b61b01a1" target="_blank">
        <span class="link-dot" style="background:#378ADD;"></span>LinkedIn
      </a>
      <a class="link-btn github" href="https://github.com/Abdelrahman1432000">
        <span class="link-dot" style="background:#888780;"></span>GitHub
      </a>
    </div>
  </div>

</div>

<script>
const devopsTools = [
  {name:'Docker',    icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg'},
  {name:'Kubernetes',icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg'},
  {name:'Ansible',   icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ansible/ansible-original.svg'},
  {name:'Jenkins',   icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jenkins/jenkins-original.svg'},
  {name:'Terraform', icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg'},
  {name:'Git',       icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg'},
  {name:'Linux',     icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg'},
];

const langs = [
  {name:'Python',    icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg'},
  {name:'Java',      icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg'},
  {name:'JavaScript',icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg'},
  {name:'C#',        icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg'},
  {name:'C++',       icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg'},
  {name:'PHP',       icon:'https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg'},
];

const aboutItems = [
  'Specializing in CI/CD pipelines, automation, and cloud-native DevOps.',
  'Working with AWS, Azure, and GCP cloud platforms.',
  'Automating infrastructure using Terraform, Ansible, CloudFormation.',
  'System administration background — 600+ users supported.',
  'Coding Instructor @ Ischool — Ministry of Communications, Egypt.',
  'Experienced in Linux, networking (CCNA, CCNP), and security.',
];

function renderChips(data, containerId) {
  const el = document.getElementById(containerId);
  data.forEach((d, i) => {
    const chip = document.createElement('div');
    chip.className = 'icon-chip';
    chip.style.animationDelay = (0.05 * i) + 's';
    chip.innerHTML = `<img src="${d.icon}" alt="${d.name}" /><span>${d.name}</span>`;
    el.appendChild(chip);
  });
}

function renderAbout() {
  const el = document.getElementById('about-grid');
  aboutItems.forEach((t, i) => {
    const item = document.createElement('div');
    item.className = 'about-item';
    item.style.animationDelay = (0.05 * i) + 's';
    item.innerHTML = `<div class="about-dot"></div><span>${t}</span>`;
    el.appendChild(item);
  });
}

renderChips(devopsTools, 'devops-grid');
renderChips(langs, 'lang-grid');
renderAbout();
</script>
</body>
</html>
