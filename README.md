const bio = {
  name: "Kanishk",
  pronouns: ["He", "Him"],
  codeWith: ["JavaScript", "Node.js", "Next.js", "Express", "Kotlin", "Jetpack Compose"],
  superpower: "Master of Swift Learning Spells 🧙‍♂️",
  hobbies: ["Gym Rat 💪", "Music Maestro 🎵", "Wanderlust Explorer 🌍", "Sketching Sorcerer ✏️"],
  currentFocus: "Crafting Android Spells with Kotlin & Jetpack 🚀",
  achievements: [
    "🛍️ Built an e-commerce store API",
    "🌐 Created my own stunning portfolio website",
    "🎮 Crafted basic games with JavaScript wizardry",
    "📱 Summoned a basic calculator Android app"
  ],
  quote: "Why do programmers prefer dark mode? Less light, fewer bugs!"
};

class Developer extends FullStackWizard {
  constructor(bio) {
    super(bio);
  }

  sayHello() {
    console.log(`Hey there! I'm ${this.bio.name}, a ${this.getAge()}-year-old coding alchemist.`);
  }

  showSuperpower() {
    console.log(`My coding superpower? I can learn new tech faster than you can say 'console.log'!`);
  }

  shareQuote() {
    console.log(`Favorite quote: "${this.bio.quote}"`);
  }
}

const me = new Developer(bio);
me.sayHello();
me.showSuperpower();
me.shareQuote();
