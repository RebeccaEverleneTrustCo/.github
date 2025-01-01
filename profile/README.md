


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
## About Medkids
Medkids is a resource to enable children interested in the field of medicine to effortlessly comprehend 
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
  - Login to staging : [Staging](https://anatomyisland.org/medkidsstaging.infinityfreeapp.com/wp-admin)
  - Step 5: Accept invitation to staging, LOGIN and starting implimenting Figma designs in Wordpress staging.
  - If you are not familar with using WordPress for web design ,get started here [Begineers to WordPress Video Resource](https://www.youtube.com/watch?v=FMCR_7xVInk)
### Workflow
  - Only the team lead is allowed to install or uninstall plugins or Themes. Reach out to team lead if you have to add or uninstall a theme or plugin
  - Design your web pages to be responsive for Mobile, Tablet and Desktop.
  - Use Custom `CSS & JS plugin` to write custom CSS and JavaScript.
  - Create and write your custom `CSS and JavaScript` in `task-name.css` and `task-name.js` files (<b>task-name</b> is the name of task you are working on and the CSS or JS should be given the project name-Just use your project name as CSS file name ). Every JavaScript file you should be witten within the  `DOMContentLoaded` `event`
    Example.
    ```js
          windows.addEventListener('DOMContentLoaded', function(){
            /**
              Add JavaScript here
            ***/
          const textContent = 'Hello world';
          
        })

    ```
    
  - For Custom CSS here is how we [class](https://rebeccaeverlenegroup.slack.com/files/U0450DR40FP/F06RNSP1C4B/20240327_124725.mp4?origin_team=T021ALT11NU&origin_channel=C020HQB61PF) elements to add custom styling or select for JavaScript.
  
  - We follow Block Element Modifier (BEM) convention to give a class name to elements.[Read more on BEM](https://css-tricks.com/bem-101/)
  - Leave a comment within the CSS and JS to show start of code and to document your code.
  - <b> CSS UNITS: </b> All CSS units should be written in  `rem`, note `1rem = 16px`.
  - Define
    ```css
          html {
      font-size:16px;
    }
        
    ```
    on your custom CSS so we can ensure that 1rem = 16px
  - For Mobile Heading and Sub Heading subtract 0.75rems from the Desktop values, base text remains 1rem.
  - For Tablet Heading and Sub Heading subtract 0.5rems from the Desktop values, base text remains 1rem.
  - <strong>Assets</strong>: All Medkids assets are hosted at [MEDKids Image Hosting repository](https://github.com/MEDkids/images) do not host images directly in production or statging WordPress.
  -  While linking to assets the link prefix should be `https://rebeccaeverlenetrustco.github.io/images/` followed by the `assets folder` followed by the `assets name` dot the extension. Example: `https://rebeccaeverlenetrustco.github.io/images/Nurse_Nurse_Playground/Nurse_Nurse_Playground_Vector.png` .
  - 
  - Export all the images from the Figma task into a folder. Name folder with project name and separate spaces with `-` or `_` or both as the case may be.Next clone the [Medkids image respository here ](https://github.com/MEDkids/images), Add your folder with images and make pull request. Leave a message in the team slack for approval.
  - Name assets exactly the way they are named in Figma file but with `underscore` when uploading to image storage. Use task name as a `prefix` before the asset name EG i am working on a task on <b>Big Energy Body</b>, i should name my file like this <b>Big_Ener_Body_`vector1`</b> `vector1` being the asset name.
  - <strong>Approval</strong>: Get approval from team leads before publishing to production.
## Issues
Visit https://github.com/MEDkids/.github to create `New Issue` regarding your task. 
### Steps
  - On the issue page click `New Issue`
  - Add a title
  - Add a description : Explain what issue you are creating. Issues can be technical problems or your uncompleted task you want to keep track off  or an uncompleted feature on a task
  - Click `Submit new issue`
Note: You are not allowed to close issue.
## Moving completed projects from staging to production

WP staging is like our development branch and WP product is like our master branch
