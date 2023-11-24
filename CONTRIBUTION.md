# Contribution (Draft)

`Awesome Satori` is a curated list of various interesting topics in the Satori community, for collecting and sharing excellent resources related to Satori, including implementations, SDKs, frameworks, tutorials, tools, and more, to help others learn, discover, and use Satori.
In order to maintain the high quality and consistency, this document introduce in detail how to contribute your work here.

English | [简体中文](./CONTRIBUTION-zh.md)

## Preparation

Before contributing your work, you will have some prerequisites:

- A GitHub account that forked this repository.
- Acknowledges or interests about Satori and you are willing to help others.
- Content that you are adding is related to Satori and either being of high quality, useful, powerful, or innovative.
- Obey the copyright or license or intellectual property rights of the original author, avoid adding any infringing or illegal content.

## Adding Content

We warmly welcome you to contribute any excellent resources related to Satori, including but not limited to the following types:

- Implementation of the Satori protocol.
- SDKs: Development tools based on the Satori protocol.
- Frameworks: Communication frameworks and applications utilizing the Satori protocol.
- Tutorials: Instructive articles or videos guiding development, deployment, testing, debugging, etc., using Satori and implementing SDKs or frameworks.
- Tools: Software, libraries, frameworks, plugins, etc., designed to enhance your efficiency or experience in Satori development.
- Articles: In-depth or comprehensive writings introducing the principles, features, advantages, and application scenarios of Satori.

### Implementations, SDKs and Frameworks

> [!NOTE]
> Implementations should be strictly protocol-based, while SDKs and frameworks should be built on the implemented protocol. For simplicity, we'll collectively refer to SDKs and frameworks as `Framework`.

Implementations, SDKs, and Frameworks are the main content of this project, and we welcome your contributions to the community. When contributing such content, there are some requirements in the following:

- Implementations, SDKs and Frameworks will be placed in separate tables, with the following fields:
   - `Name`: Your project's name, sorted alphabetically from A-Z (official projects will be listed at the top if not individually distinguished).
   - `Author`: Your name, i.e., your GitHub account name (use name instead of username, as the name is unique on GitHub).
   - `Language`: The programming language in which the project is written; **This only indicates the language used to write the project.**
- Ensure that both `Name` and `Author` have a link pointing to the respective homepage.
- If you have derived multiple projects (e.g., Implementation -> SDK), these projects should be in the same cell, separated by `w/`<sup>[1]</sup>;
   - Example:
      | Name | Author | Language |
      | ---  | ---    | ---      |
      | [SPPS](https://github.com/im-patory/spps) w/ [Patory](https://github.com/im-patory/patory) | [Lipraty](https://github.com/Lipraty) | PHP |
   - In the example above, `SPPS` and `Patory` are both projects by `Lipraty`, and `Patory` is a dependency of `SPPS`.
- If you, as the same author in the same language, have written multiple projects that are at the same level, they should be placed in the same cell, separated by `<br>`;
   - SDKs and Frameworks should be in the same cell, separated by `<br>`;
   - As `<br>` increases the height of cells in the table, try not to split excessively to ensure that the number of projects in each cell does not exceed 3;
   - Example:
      | Name | Author | Language |     |
      | ---  | ---    | ---      | --- |
      | [Yutori-QQ](https://github.com/Nyayurn/Yutori-QQ) <br>[Yutori-QQ-SpringBootStarter](https://github.com/Nyayurn/Yutori-QQ-SpringBootStarter) | [@Nyayurn](https://github.com/Nyayurn) | Java | Java **QQ** bot Framework SDK based on Satori Protocol |
   - In the example above, `Yutori-QQ` and `Yutori-QQ-SpringBootStarter` are both projects by `Nyayurn`, and `Yutori-QQ-SpringBootStarter` is at the same level as `Yutori-QQ`.
- You should provide detailed descriptions of your projects in the README file:
  - For implementations of the Satori protocol, include information such as the protocol version and the degree of protocol implementation.
  - For SDKs and Frameworks, provide usage instructions, example code, API documentation, and other relevant information in the README file.

### Toolset

TODO.

### Tutorials and Articles

TODO.

## Contribution Process

If you would like to contribute to this project, please follow the steps below:

- Clone the repository after forking it.
- Create a new branch locally and add the content you wish to contribute to the `README.md` file.
- When adding content, adhere to Markdown syntax and formatting guidelines, ensuring correct indentation, spacing, punctuation, etc.
- Provide a brief description for each added content, explaining what it is.
- Check for duplicate, invalid, or incorrect links in your additions and correct or remove them.
- Commit your changes and push them to your forked repository.
- Create a Pull Request on GitHub, requesting to merge your branch into the main branch.
   - Ensure the PR title follows the format: `Update: [project name]`.
- Briefly explain in the Pull Request body what content you added, why you believe it's awesome, and confirm that you've followed the guidelines above.
- Wait for the maintainer to review and respond to your Pull Request. If necessary, make modifications or additions based on the feedback.

## Contribution Review

After you've submitted a Pull Request, the maintainers will promptly review your contribution and provide feedback and suggestions. Please keep the following in mind:

- Your Pull Request may be accepted, rejected, modified, or merged, depending on whether the content you added aligns with the project's theme and quality standards, and if it adheres to the requirements outlined in this guide.
- You might receive comments or questions from maintainers or other contributors. Please respond in a friendly and courteous manner, providing necessary explanations or evidence.
- If you receive suggestions for modifications or additions, make adjustments promptly and update your Pull Request. If you disagree with the suggestions, express your opinions in a rational and objective manner, providing reasonable justifications or evidence.
- If your Pull Request is accepted and merged, please refrain from deleting your forked repository or branch to facilitate future updates and maintenance.

Lastly, a big thank you for your efforts in contributing to the Satori community ecosystem! We hope you enjoy the contribution process and gain knowledge, enjoyment, and a sense of accomplishment. If you have any questions or feedback, feel free to open an issue to communicate with us.

------

[1]: `w/` is an abbreviation for `with`, indicating a subordinate relationship.
