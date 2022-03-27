



<div align="center">
  
  ![mime hero banner](https://cdn.discordapp.com/attachments/792686378366009354/957495249419255808/unknown.png)
  
  ### A blazing fast query based meme generation API
  ###### mime is currently closed source, this repo serves as a showcase for the project

  ---
  
</div>

### About
I created mime because I wanted a fast and easy way to create and share memes with my friends. 

Mime aims to be as easy to use as possible, for both consumers and developers. Memes are created on the fly based on query parameters in meme url making it extremely easy for developers to integrate mime into their apps. It also has [**Playground**](https://mime.nathanferns.xyz/playground) for quickly creating memes yourself.

<img src="https://cdn.nathanferns.xyz/memes/chaddoge?chad=using_mime&virgin=making_them_urself" height="250">



### Highlights

- Supports both **Gifs** and **Images** up to **10MB**
- Memes can have layers with complex transformations
- Memes can be stacked up to 5 times deep
- Any text on a meme will always be wrapped and sized for maximum readibilty
- Any meme can be edited just by editing it's url

<img src="https://cdn.nathanferns.xyz/memes/spiderman.gif?image=https%3A%2F%2Fmedia.tenor.com%2Fimages%2Ff9d4460786929591059f3feb86c624be%2Ftenor.gif&text=thats%20pretty%20cool" height="250"> <img src="https://cdn.nathanferns.xyz/memes/metaverse?image=https%3A%2F%2Fcdn.nathanferns.xyz%2Fmemes%2Fchaddoge%3Fchad%3Dusing_mime%26virgin%3Dmaking_them_urself" height="250">

---

### Structure 

```yaml
.
├── mime-core           # the heart of mime
│   ├── api             # api for requesting memes
│   └── stacks          # template driven image manipulation tool
├── mime-stats          # tiny and fast statistics api for mime
└── mime-site           # WIP site for learning about and testing mime
    └── mime-editor     # WIP meme editor to create mime templates
```

### Tech Stacks

#### mime-core
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> <img src="https://cdn.discordapp.com/attachments/792686378366009354/957533071043874866/unknown.png" alt="fast api" width="40" height="40"> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> 

#### mime-stats 
<a href="https://www.rust-lang.org" target="_blank" rel="noreferrer"> <img src="https://cdn.discordapp.com/attachments/792686378366009354/957538675397386250/rustacean-flat-happy.png" alt="rust" height="40"/> </a>

#### mime-site
 <a href="https://svelte.dev" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg" alt="svelte" width="40" height="40"/> </a>  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>  <a href="https://sapper.svelte.dev/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/bestofjs/bestofjs-webui/master/public/logos/sapper.svg" alt="sapper" width="40" height="40"/> </a> 
 
---

### Next Steps
###### ...i'll fill this out soon


### Contact
Email: nathaniel.s.fernandes@gmail.com

Discord: `nathan#3724`

 


