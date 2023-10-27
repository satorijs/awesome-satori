# Contribution (Draft)

`Awesome Satori` is a resource list that showcases various interesting topics in the Satori community, aiming to collect and share excellent resources related to Satori, including protocol implementations, SDKs, frameworks, tutorials, tools, and more, to help others learn, discover, and use Satori.
To ensure quality and consistency, this document will describe in detail how you should contribute your work.

## Preparation

Before contributing your work, we need some preparation:

- Have a GitHub account and fork this repository.
- Have some understanding or interest in Satori and be willing to provide valuable information and help to the community.
- Ensure that the content you add is related to Satori and is of high quality, useful, interesting, or innovative.
- Respect the original author's copyright and intellectual property rights and avoid adding any infringing or illegal content.

## Adding Content

This project welcomes you to add any excellent resources related to Satori, including but not limited to the following types:

- Satori protocol implementations.
- SDKs: Development tools based on the Satori protocol.
- Frameworks: Frameworks or applications that use the Satori protocol for communication.
- Tutorials: Guided articles or videos on how to use Satori and Satori protocol implementations SDKs/Frameworks for development, deployment, testing, debugging, etc.
- Tools: Software, libraries, frameworks, plugins, etc. that help you improve your Satori development efficiency or experience.
- Articles: In-depth or extensive articles on the principles, features, advantages, application scenarios, etc. of Satori.

### Implementations, SDKs and Frameworks

When adding `implementation/SDK/Framework` contribution content, we will make the following requirements:

- Implementations, SDKs and Frameworks will be placed in tables separately with the following fields:
   - `Name`: The name of your project, sorted by English alphabet A-Z (if not distinguished separately, official projects will be at the top)
   - `Author`: The author name, which is you (should use name instead of username. Because name is unique on GitHub)
   - `Language`: The language used to write the project. **This only indicates the language used to write the project**.
- Please ensure that both `Name` and `Author` have an address pointing to the corresponding homepage.
- If you have derived multiple projects (such as implementation -> SDK), these projects should be in the same cell and use `w/` to indicate the subordinate relationship.
   - Example:
      | Name | Author | Language |
      | ---  | ---    | ---      |
      | SPPS w/ Patory | Lipraty | PHP |
- If you have written multiple projects under the same author and language but they are all at the same level, you should use `<br>` to put multiple projects in same cell.
   - Example:
      | Name | Author | Language |     |
      | ---  | ---    | ---      | --- |
      | Yutori-QQ <br>Yutori-QQ-SpringBootStarter | @Nyayurn | Java | Java **QQ** bot framework SDK based on Satori Protocol |

### Toolset

TODO.

### Tutorials and Articles

TODO.

## Contribution Process

If you want to add content to this project, please follow these steps:

- Clone the forked repository to your local machine.
- Create a new branch locally and add the content you want to contribute in the readme.md file.
- When adding content, please follow the Markdown syntax and format specifications, using correct indentation, spaces, punctuation marks, etc.
- Provide a short description for each added content explaining what it is.
- Check whether the content you added has duplicate, invalid or incorrect links and correct or delete them in time.
- Commit your changes and push them to your forked repository.
- Create a pull request on GitHub requesting to merge your branch into awesome-satori's main branch.
   - Please ensure that the PR title format is: `Update: [project name]`.
- In the body of the pull request briefly explain what content you added why you think it is awesome and whether you followed the above guidelines.
- Wait for awesome-satori's maintainers to review and reply to your pull request if necessary please modify or supplement according to feedback.

## Contribution Review

After submitting your pull request awesome-satori's maintainers will review your contribution as soon as possible and give you feedback and suggestions. Please note the following points:

- Your pull request may be accepted rejected modified or merged depending on whether the content you added meets the theme and quality standards of this project and whether you followed the requirements of this guide.
- You may receive comments or questions from maintainers or other contributors please reply politely and provide necessary explanations or evidence.
- If you receive suggestions for modification or supplementation please adjust as soon as possible and update your pull request. If you disagree with the suggestions please express them rationally and objectively and provide reasonable reasons or evidence.
- If your pull request is accepted and merged please do not delete your forked repository or branch for subsequent updates and maintenance.

Finally thank you very much for your efforts to the satori community ecosystem! We hope you enjoy the contribution process and gain knowledge fun and a sense of accomplishment from it. If you have any questions or feedback please feel free to open an issue and communicate with us.
