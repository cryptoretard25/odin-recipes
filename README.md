<section>
  <h3><a href="#introduction" class="anchor-link">Introduction</a></h3>

  <p>
    It’s time to put all of the HTML knowledge you have been acquiring so far
    into practice. In this project, you are going to build a basic recipe
    website.
  </p>

  <p>
    The website will consist of a main index page which will have links to a few
    recipes. The website won’t look very pretty by the time you’ve finished. Not
    unless you’re into
    <a
      href="https://brutalistwebsites.com/"
      target="_blank"
      rel="noopener noreferrer"
      >brutalist web design</a
    >, that is.
  </p>

  <p>
    But it’s important to keep in mind that this project is just to build your
    HTML chops; we will revisit this project in the future to style it up with
    CSS.
  </p>
</section>
<section id="setting-up-your-projects-github-repository">
  <h3>
    <a href="#setting-up-your-projects-github-repository" class="anchor-link"
      >Setting Up Your Project’s GitHub Repository</a
    >
  </h3>

  <p>
    As mentioned in the
    <a
      href="https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/introduction-to-git"
      target="_blank"
      rel="noopener noreferrer"
      >introduction to Git</a
    >, you’ll want to organize all your projects like a portfolio and link them
    to GitHub so it can be seen by others.
  </p>

  <p>
    If you do not know how to set up a repository, follow the instructions found
    in
    <a
      href="https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/git-basics"
      target="_blank"
      rel="noopener noreferrer"
      >Git Basics</a
    >
    to learn how.
  </p>

  <ol>
    <li>
      <p>
        Create a new repo for this project on GitHub.com and call it
        <code>odin-recipes</code>.
      </p>
    </li>
    <li>
      <p>
        Move that repository onto your local machine, inside the
        <code>repos</code> folder that you previously created in the Git Basics
        lesson. The command should look like
        <code>git clone git@github.com:username/odin-recipes.git</code> (use
        SSH).
      </p>
    </li>
    <li>
      <p>
        Now <code>cd</code> into the <code>odin-recipes</code> project directory
        that is now on your local machine.
      </p>
    </li>
    <li>
      <p>
        Set up your <code>README.md</code> file and write a brief introduction
        describing what the current project is and what skills you will have
        demonstrated once you have completed it. (You can also do this as a
        self-reflection at the end of the project, which is a good way to review
        what you have learned.)
      </p>
    </li>
  </ol>

  <p>If you are having trouble:</p>

  <ul>
    <li>
      <p>
        All Git commands need to be run from inside your project’s folder (did
        you forget to <code>cd</code> into the
        <code>odin-recipes</code> folder?).
      </p>
    </li>
    <li>
      <p>
        Ensure you followed the steps
        <a
          href="/paths/foundations/courses/foundations/lessons/setting-up-git#step-2-configure-git-and-github"
          >here on Step 2.3</a
        >
        to clone from GitHub with SSH.
      </p>
    </li>
    <li>
      <p>
        Refer to the
        <a
          href="https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/git-basics"
          target="_blank"
          rel="noopener noreferrer"
          >workflow</a
        >
        in the Git Basics Lesson.
      </p>
    </li>
  </ul>

  <h4 id="tips-on-when-to-commit">Tips on When to Commit</h4>
  <p>
    Don’t forget everything we went over in the
    <a
      href="https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/commit-messages"
      target="_blank"
      rel="noopener noreferrer"
      >previous lesson</a
    >
    about commit messages!
  </p>

  <p>
    When you’re building your project, you will probably end up doing several
    <code>git add</code> + <code>git commit</code> cycles before being ready to
    push it up to GitHub with <code>git push origin main</code>.
  </p>

  <p>
    When writing code, it’s considered best practice to commit early and often.
    Commit every time you have a meaningful change in the code. This will create
    a timeline of your progress and show that your finished code didn’t appear
    out of nowhere.
  </p>

  <p>
    After you have entered <code>git push origin main</code>, switch over to
    your browser and open your repository on GitHub. You should now see all the
    files you just pushed.
  </p>

  <p>Okay, that’s enough Git for the moment – time to actually build stuff!</p>
</section>
<section id="assignment">
  <h3><a href="#assignment" class="anchor-link">Assignment</a></h3>
  <h4 id="iteration-1-initial-structure">Iteration 1: Initial Structure</h4>
  <ol>
    <li>
      Within the <code>odin-recipes</code> directory, create an
      <code>index.html</code> file.
    </li>
    <li>
      Fill it out with the usual boilerplate HTML and add an
      <code>h1</code> heading “Odin Recipes” to the body.
    </li>
  </ol>

  <h4 id="iteration-2--recipe-page">Iteration 2: Recipe Page</h4>

  <ol>
    <li>
      Create a new directory within the <code>odin-recipes</code> directory and
      name it <code>recipes</code>.
    </li>
    <li>
      Create a new HTML file within the <code>recipes</code> directory and name
      it after the recipe it will contain. For example
      <code>lasagna.html</code>. You can use the name of your favorite dish or,
      if you need some inspiration, you can
      <a
        href="https://www.allrecipes.com/"
        target="_blank"
        rel="noopener noreferrer"
        >find a recipe to use here</a
      >.
    </li>
    <li>
      For now, just include an <code>h1</code> heading with the recipe’s name as
      its content.
    </li>
    <li>
      Back in the <code>index.html</code> file, add a link to the recipe page
      you just created. Example: Under the
      <code>&lt;h1&gt;Odin Recipes&lt;/h1&gt;</code> heading, write out the link
      like so:
      <code>&lt;a href="recipename.html"&gt;Recipe Title&lt;/a&gt;</code>. The
      text of the link should again be the recipe name.
    </li>
  </ol>

  <h4>Iteration 3: Recipe Page Content</h4>

  <p>Your new recipe page should have the following content:</p>

  <ol>
    <li>
      <p>
        An image of the finished dish under the h1 heading that you added
        earlier. You can find images of the dish on Google or the
        <a
          href="https://www.allrecipes.com/"
          target="_blank"
          rel="noopener noreferrer"
          >recipe site</a
        >
        we linked to earlier.
      </p>
    </li>
    <li>
      <p>
        Under the image, it should have an appropriately sized “Description”
        heading followed by a paragraph or two describing the recipe.
      </p>
    </li>
    <li>
      <p>
        Under the description, add an “Ingredients” heading followed by an
        <strong>unordered list</strong> of the ingredients needed for the
        recipe.
      </p>
    </li>
    <li>
      <p>
        Finally, under the ingredients list, add a “Steps” heading followed by
        an <strong>ordered list</strong> of the steps needed for making the
        dish.
      </p>
    </li>
  </ol>

  <h4>Iteration 4: Add More Recipes</h4>

  <ol>
    <li>
      Add two more recipes with identical page structures to the recipe page
      you’ve already created.
    </li>
    <li>
      Don’t forget to link to the new recipes on the index page. Also, consider
      putting all the links in an unordered list so they aren’t all on one line.
    </li>
  </ol>
  <p>
    Your links won’t be flashy, but for now just focus on building them out.
  </p>
</section>
<section id="viewing-your-project-on-the-web">
  <h3>
    <a href="#viewing-your-project-on-the-web" class="anchor-link"
      >Viewing Your Project on the Web</a
    >
  </h3>

  <p>
    If you want to show your work (the project) to others, or submit a solution
    below, you will need to publish your site so that others can access it from
    the web, rather than just on your local machine. The good news is that if
    you have your project on GitHub (as described above), doing this is
    incredibly simple.
  </p>

  <p>
    GitHub allows you to publish web projects directly from a GitHub repository.
    Doing this will allow you to access your project from
    <code>your-github-username.github.io/your-github-repo-name</code>.
  </p>

  <p>
    There are a couple of ways to go about doing this, but the simplest is this:
  </p>

  <ul>
    <li>
      make sure that the main HTML file of your project is called
      <code>index.html</code>. If it is not, you will need to rename it.
    </li>
    <li>go to <strong>your GitHub repo</strong> on the web.</li>
    <li>
      click on the <strong>Settings</strong> button from the panel at the top.
    </li>
    <li>click on <strong>Pages</strong> on the left side bar.</li>
    <li>
      change the <strong>Branch</strong> from <em>none</em> to
      <em>main branch</em> and click Save.
    </li>
    <li>
      it may take a few minutes (the GitHub website says up to 10, but we’ve
      seen it take up to an hour. Do not add a “theme” to your project, or you
      may have git conflicts, instead, be patient.) but your project should be
      accessible over the web from
      <code>your-github-username.github.io/your-github-repo-name</code>
      (obviously substituting your own details in the link).
    </li>
  </ul>
</section>
