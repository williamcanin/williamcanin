<!-- ### <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> Hi there -->

<!--
**williamcanin/williamcanin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

<!--
```python
#!/usr/bin/env python3

print("Hello, World!")
print("My name is William, and I am a programming and hacking enthusiast.")

MY_ENVIRONMENT = "https://github.com/williamcanin/my_environment"

workflow = {
    "my_main_tech_stack": {
        "Languages": ["Rust", "Python", "Shell Script"],
        "Frameworks": ["Django"],
        "Frontend": ["HTML", "CSS", "SASS", "Bootstrap", "Jekyll"],
        "Database": ["PostGreSQL"],
        "Tools": ["VSCode", "Vim", "PyCharm", "Git", "DBeaver"],
        "OS": ["Linux"]
    },
}

follow_me = {
    "YouTube": "https://www.youtube.com/c/williamcanin",
}
```
<img width="340px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=williamcanin&hide=html,coffeescript,makefile,mako,pug,batchfile,ruby,tsql,procfile&hide_border=true&layout=compact&theme=buefy"/> <img width="405px" src="https://github-readme-stats.vercel.app/api?username=williamcanin&theme=buefy&hide_border=true"/>
-->

```rust
// main.rs

use std::collections::HashMap;

fn main() -> Result<(), Box<dyn std::error::Error>> {

  let workflow: HashMap<&str, HashMap<&str, Vec<&str>>> = HashMap::from([
    (
        "My Main Tech Stack",
        HashMap::from([
            ("Languages", vec!["Python", "Shell Script"]),
            ("Frameworks", vec!["Django"]),
            ("Frontend", vec!["HTML", "CSS", "SASS", "Bootstrap", "Jekyll"]),
            ("Database", vec!["PostGreSQL"]),
            ("Tools", vec!["VSCode", "Vim", "PyCharm", "Git", "DBeaver"]),
            ("OS", vec!["Linux"]),
        ]),
    ),
  ]);

  let yt_link: &str = "https://www.youtube.com/c/williamcanin";

  println!("Hello, World!");
  println!("My name is William, and I am a programming and hacking enthusiast.");

  for (key, value) in &workflow {
    println!("{}:", key);
    for (inner_key, inner_value) in value {
        println!("  {}: {:?}", inner_key, inner_value);
    }
  }

  println!("YouTube::> {}", yt_link);

  Ok(())

}
```

