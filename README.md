This project demonstrates the integration of Editor.js, a block-styled editor for rich media content creation, with Stimulus, a modest JavaScript framework, within a Rails 7 application. By combining these technologies, we aim to provide a seamless and intuitive editing experience for users, allowing them to create and manage various types of content effortlessly.

Features
**Editor.js Integration**: Utilizes Editor.js to enable users to create structured content with ease, offering a wide range of block types such as paragraphs, headings, lists, quotes, and more.
**Stimulus Framework**: Leverages Stimulus for efficient management of interactive elements within the editor interface, enhancing user experience and responsiveness.
**Rails 7 Compatibility**: Built and tested on Rails 7, ensuring compatibility with the latest version of the framework and taking advantage of its features and improvements.

**Setup Instructions**
Clone the repository to your local machine.
Navigate to the project directory.
Install dependencies by running bundle install and yarn install.
Set up the database with rails db:create and rails db:migrate.
Start the Rails server with rails server.
Access the application in your browser at the specified localhost address.
Usage
Upon accessing the application, users can navigate to the content creation interface.
Utilize the Editor.js editor to compose and format content as desired, leveraging the various available block types and editing features.
Save and publish content seamlessly within the application.
Contribution
We welcome contributions from the community to enhance and improve this project further. Feel free to submit bug reports, feature requests, or pull requests via GitHub.

License
This project is licensed under the MIT License.

Acknowledgments
Editor.js: A special thanks to the creators and contributors of Editor.js for providing a powerful and flexible tool for content creation.
Stimulus: We extend our appreciation to the creators of Stimulus for offering a lightweight and pragmatic framework for building interactive interfaces in web applications.

 **To set up this application, follow these steps:**

Create a New Rails Application:

rails new video -j esbuild -c bootstrap && cd video && code .

**Generate Scaffold for Initial Content Model:**


rails g scaffold title content:json

**Generate Stimulus Controller for Editor:**


rails g stimulus editor

**Install Editor.js and its Dependencies:**
yarn add @editorjs/editorjs
yarn add @editorjs/header @editorjs/list @editorjs/paragraph @editorjs/code

**Generate Initial Scaffold**:
rails g scaffold article title:string content:json

**Run Database Migrations:**
rails db:migrate
bin/dev
or you can take clone this repo.
