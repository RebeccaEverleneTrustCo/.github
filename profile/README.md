


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
## About Medkids
Medkids is resource to enable children interested in the field of medicine to effortlessly comprehend 
what a career in the field of medicine entails.

## Contribution guidelines
Our tech stack for Medkids is <strong>WordPress</strong> and custom CSS and JavaScript.
### How to get started
Here are stpes to get started contributing to the project
  - Step 1: Get onboarded to the Medkids web developemnt slack channel.
  - Step 2: Get assigned a design file by Tamara.
  - Step 3: Get Invitation to Monday.com from Tamara where you can access the design files.
  - We have 2 <strong>WordPress</strong> sites, one is staging, for trying out ideas before is goes to production. Your approaved staging goes to production.
  - Step 4: Send your email for invitation to staging.
  - Step 5: Accept invitation to staging, LOGIN and starting implimenting Figma designs in Wordpress staging.
  - If you are not familar with using WordPress for web design ,get started here [Begineers to WordPress Video Resource](https://www.youtube.com/watch?v=FMCR_7xVInk)
### Workflow
  - Only the team lead is allowed to install or uninstall plugins or Themes. Reach out to team lead if you have to add or uninstall a theme or plugin
  - Design your web pages to be responsive for Mobile, Tablet and Desktop.
  - Use Custom `CSS & JS plugin` to write custom CSS and JavaScript.
  - Write your custom `CSS and JavaScript` in `myTaskName.css` and `myTaskName.js` files. Every JavaScript file you should be witten within the  `DOMContentLoaded` `event`
    Example.
    ```js
          windows.addEventListener('DOMConentLoaded', function(){
            /**
              Add JavaScript here
            ***/
          const textContent = 'Hello world'
          
        })

    ```
    
  - For Custom CSS here is how we [class](https://rebeccaeverlenegroup.slack.com/files/U0450DR40FP/F06RNSP1C4B/20240327_124725.mp4?origin_team=T021ALT11NU&origin_channel=C020HQB61PF) elements to add custom styling or select for JavaScript.
  - We follow Block Element Modifier (BEM) convention to give a class name to elements.[Read more on BEM](https://css-tricks.com/bem-101/)
  - Leave a comment within the CSS and JS to show start of code and to document your code.
  - <strong>Assets</strong>: All Medkids assets are hosted at [MEDKids Image Hosting repository](https://github.com/MEDkids/images) do not host images directly in production or statging WordPress.
  - Name assets exactly the way they are named in Figma file but with `underscore` when uploading to image storage EG `poke ball` becomes `poke_ball`.
  - <strong>Approval</strong>: Get approval from team leads before publishing to production.


