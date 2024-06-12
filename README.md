# 1. **Introduction**:
Firstly I'd like to take the opportunity to thank you for taking your time to review my submission, and for your consideration for the role.

# 2. **Considerations**:
The project is made up of two folders namely `Frontend` and `Backend` each containing the appropriate code for their respective functions. The two folders are actually sub modules in the respository and each have their individual repositories which can be found in the .gitmodules file.

## Backend
This contains the barebones code provided for the backend application. I didn't think it was necessary to modify anything here, although I thought it would be prudent to add an `id` key for Frontend operations which I did.

##  Frontend
I used `Vite` to build the project, this was a decision based on personal preference mainly due to performance, and a more robust application out of the box. I also thought it would be a good idea to use `Typescript` instead of Javascript to minimize on compile errors. I also decided to incorporate `Tailwind` to be able to quicky and dynamically add styling to the components without bloating the CSS files considering the size of the project.
I also intially considered using the Atomic Design pattern to have a more consistent design, but I decided that it would be overkill due to the size of the project.
I decided to futher modularize the code by adding a Providers tree instead of bloating the entry point of the application, which would also improve readability.

# 3. **Setting up Environment for Frontend**:

To setup the Frontend application access the /frontend directory add an .env.local file add the appropriate values based on the defaults in the .env.example file.

# 4. **Running the Project**:
Each of the projects in the backend and frontend have their individual ``package.json`` files with scripts to run them but I thought it would be a good idea to initialize an npm project in the root directory to make it easy to run both projects. To quickly run both projects(Frontend & Backend) from the root directory, run the following commands on your terminal:

```npm run setup:all```

```npm run run:all```


Lastly thank you again for taking your time to review this, if you have any comments that can help improve this project or questions feel free to drop me an email at <a href="mailto:kengeene@gmail.com">kengeene@gmail.com</a>
