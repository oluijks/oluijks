## Hi there 🖖

<!--
**oluijks/oluijks** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

### About Me

I'm Olaf, a 52-year-old developer from the Netherlands, married to Luba and usually found somewhere behind a terminal. I love open source, programming, and getting lost in reading and writing poetry. When I'm not tinkering with code, I'm probably walking along the beach with our bull terrier, Bogdan, listening to the sea and thinking about the next thing I'll build and never quite finish.

```ts
type Stack =
  | 'Svelte'
  | 'SvelteKit'
  | 'TypeScript'
  | 'Node.js'
  | 'SQLite'
  | 'Rust'
  | 'Go'
  | 'C/C++';

interface DevProfile {
  name: string;
  dob: Date;
  url: string;
  location: string;
  stack: Stack[];
  loves: string[];
  tools: string[];
  currently: {
    learning: string;
    building: string;
  };
  funFact: string;
}

export const olaf = {
  name: 'Olaf Luijks <olafluijks@proton.me>',
  dob: new Date('1973-03-09T06:24:00'),
  url: 'https://blog.luba.dev',
  location: 'Somewhere behind a terminal',
  stack: ['Svelte', 'SvelteKit', 'TypeScript', 'Rust', 'Go'],
  loves: [
    'Linux', 
    'APIs',
    'music from Bach to SOAD',
    'terminal',
    'poetry',
    'open source',
    'quiet refactors',
    'my wife luba and bull terrier bogdan'
  ],
  tools: ['Neovim', 'LazyGit', 'Linux', 'VS Code'],
  currently: {
    learning: 'QML, QuickShell, Rust, Ukrainian, Cyber Security',
    building: 'a web-based writing app called Spleen'
  },
  funFact: 'Will absolutely over-engineer any side project I never finish.'
} satisfies DevProfile;

```

[🌐 Blog](https://blog.luba.dev) · [🔐 GPG key](https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x107D2CD87A4A2E21)
