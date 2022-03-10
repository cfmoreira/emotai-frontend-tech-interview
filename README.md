# emotai-frontend-tech-interview

Repository for Technical Interview Challenges - Frontend Edition&trade;

This challenge uses the [Electron React Boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate). Using this boilerplate, you will be tasked with creating a desktop app to view data from a smart scale. Your goal is to create a dashboard visualization for the user to check his health data status.

## Instructions

1. Setup a **private** mirror of this repository (to preserve your anonimity). See the [documentation on mirroring a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository).
    - create a new private repository on github.com;
    - create a bare clone of this repository;
    - mirror-push to the private repository you have created;
    - finally, remove the temporary local repository you created earlier.

     When you have your private clone of the repository, add EMOTAI team members as private collaborators.

   - [Daniel](https://github.com/chipimix)
   - [Carlos](https://github.com/cfmoreira)

2. Complete the designated tasks defined below.

3. When you are finished, email the link to the repository to <careers@emotai.tech>.

4. That's it! We will review your work and get in touch asap.

## The challenge

1. Design your best single page dashboard for fitness and health data!
   - You must include information regarding the most recent measurements - for the following metrics: HR, Body Weight, BMI and Score. Additionally, you must specify if the  latest measurement changed compared to a previous benchmark.
   - You must include one or more charts of your choice which best represent the user's progress - for the following metrics: Body Fat, Muscle Mass and Hydration Level. Additionally, the user must be able to choose the time domain out of the following options: latest week or latest month.
   - Try to either follow or improve on the example wireframe design below.

2. Access the mock dataset with an HTTP GET request on https://elasticbeanstalk-eu-west-1-446251264147.s3.eu-west-1.amazonaws.com/tech-interview/scale-data.json.

3. Use the React `useEffect` hook to fetch the example health data from the provided JSON file, and save it to state by using the React `useState` hook.

4. Make the layout responsive with at least one breakpoint (your choice as to how it looks on a smaller screen width).

5. Create unit tests for each new components you created (see App.test.tsx for reference).

![Example Dashboard](/assets/example-dashboard.png)

**Disclaimer:** All provided datasets were randomly generated and do not in any way represent real health data.

GL&HF!
