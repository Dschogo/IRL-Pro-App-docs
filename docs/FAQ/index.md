# FAQ

## Contributing

??? question "How can I contribute?"
    You can contribute by submitting a pull request/issue/discussion to the [GitHub repository](https://github.com/Dschogo/IRL-Pro-App-docs). If you're not familiar with GitHub, you can also submit your contribution by discord on the [IRL PRO DISCORD](https://discord.gg/irlpro) in the #Knowledgebase thread.
    [click me after joining the discord, to find the thread easy](https://discord.com/channels/996502486535901306/1205505679889272872)

??? question "What can I contribute?"
    Basically anything,

    - Typos
    - New content (e.g. new phone tests, guides, improvements)

??? question "How do I add a Phone?"
    You can add a phone by creating a new markdown file in the `docs/Phones` directory. The file should be named after the phone model (e.g. `G8s.md`) in a subfolder named after the manufacturer (e.g. `LG/G8s.md`).

    ```yaml
    ---
    tags:
        - good 30fps
    ---
    # Zenfone 9 - 2022

    !!! success "Works great"
        - good thing {{ good }}
        - average {{ mid }}
        - bad {{ bad }}
    ```

    After the front matter, you can add the content of the phone test. (view the [LG G8s](https://github.com/Dschogo/IRL-Pro-App-docs/blob/main/docs/Phones/LG/G8s.md?plain=1) for an example)
