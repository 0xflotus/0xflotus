### Hi there 👋

```js
(function (length, c) {
    Array.from({ length }, (_, i) => i + 1)
        .map(e => c.repeat(e).padStart(length, '\u0020') + c.repeat(e - 1))
        .concat(Array.from({ length: length / 3 }, (_, i) => i + 1)
            .map(() => c.repeat(length / 3).padStart(length + length / 7, '\u0020')))
        .concat(' __  __                       __  __     __  __           ')
        .concat('|  \\/  | ___ _ __ _ __ _   _  \\ \\/ /    |  \\/  | __ _ ___ ')
        .concat('| |\\/| |/ _ \\ \'__| \'__| | | |  \\  /_____| |\\/| |/ _` / __|')
        .concat('| |  | |  __/ |  | |  | |_| |  /  \\_____| |  | | (_| \\__ \\')
        .concat('|_|  |_|\\___|_|  |_|   \\__, | /_/\\_\\    |_|  |_|\\__,_|___/')
        .concat('                       |___/                              ')
        .forEach(_ => console.log(_));
})(0x2A >> 1, '\u002A')
```

```python
print('👨🏻‍💻 by day && night 😎')
```

```prolog
job_title(X) :-
    member(X, ['Fullstack Developer', 'Software Engineer', 'Security Researcher', 'Data Scientist']),
    \+ member(X, ['Consultant']).
```

### About

- Open Source Code Explorer, Enthusiast and ~Archeo~ ~Arkeolo~ Archaeologist, that's it!


![0xflotus' github stats](https://github-readme-stats.vercel.app/api?username=0xflotus&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true&include_all_commits=true&layout=compact)
![0xflotus' top langs](https://github-readme-stats.vercel.app/api/top-langs?username=0xflotus&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&hide=swift,scss&langs_count=10&layout=compact)

<!--
**0xflotus/0xflotus** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

[![](https://komarev.com/ghpvc/?username=0xflotus&color=green)](https://github.com/0xflotus)
