class Developer {
  constructor() {
    this.language = ["JavaScript", "Python", "HTML", "CSS3];
    this.frameworks = ["React", "Express", "Firebase"];
    this.version = "Always Beta";
  }

  work() {
    console.log("Refactoring life decisions...");
  }

  debug() {
    while (true) {
      try {
        this.work();
        break;
      } catch (error) {
        console.warn("Fixed one bug, created 10 more...");
      }
    }
  }
}

const me = new Developer();
me.debug();

🖤 What I Do
------------

*   parent.killChild(this); // RIP old ideas
    
*   document.body.removeChild(document.body.firstChild); // You saw nothing
    
*   setTimeout(() => { document.body.innerHTML = ""; }, 3000); // Goodnight...
    
*   CSS: div:nth-child(666) { display: none; } // Vanished into the abyss
    
*   window.close(); // You can't escape
    
*   debug(); // Error: Debugging not found
    
*   let orphan = document.querySelector(".child"); orphan.remove(); // No one will notice
