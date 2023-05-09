# To-do list exercise

This exercise is designed to evaluate your programming skills and knowledge of
Git.

The exercise consists of two parts:

1. To-Do List Application
2. Git Exercise

## Part 1: To-Do List Application

Your task is to implement a to-do list application using Rust. The application
should allow users to create new tasks, mark tasks as completed, and view a list
of all tasks.

Here are the specific requirements for the application:

* Users should be able to add new tasks to the to-do list.
* Users should be able to mark tasks as completed.
* Users should be able to view a list of all tasks, with completed tasks
  displayed separately from incomplete tasks.
* Tasks should be persisted across application launches.
* The application should have a CLI interface, with subcommands for adding
  tasks, marking tasks as completed, and viewing the task list.

### Example Usage

Here's an example of how the application should work:

```sh
# Add a new task
$ todo add "Buy groceries"

# Add another task
$ todo add "Do laundry"

# List all tasks
$ todo list
1. [ ] Buy groceries
2. [ ] Do laundry

# Mark the first task as completed
$ todo complete 1

# List all tasks again
$ todo list
1. [x] Buy groceries
2. [ ] Do laundry
```

### Bonus Points

You can earn bonus points by implementing any of the following additional
features:

* Allowing users to delete tasks.
* Allowing users to delete all completed tasks.
* Adding due dates to tasks and displaying tasks that are overdue or due soon.
* Prioritizing tasks with a "high" or "low" priority level.
* Allowing users to group tasks into categories or projects.
* Adding a user authentication system, where each user has their own separate
  to-do list.

### Tips

Here are some tips to help you complete the exercise successfully:

* Use the Rust Programming Language book as reference: https://doc.rust-lang.org/book/
* Use external libraries (i.e., crates) when appropriate, but be sure to explain
  why you chose to use them.
* Write clear and concise code comments to explain what your code is doing.
* Use Rust's built-in testing framework to test your code.
* Use Rust's `clap` crate to create a CLI interface for your application.
* Use Rust's `serde` crate to serialize and deserialize tasks to and from disk.
* Use Rust's `serde_json` crate to serialize and deserialize in JSON format.

## Part 2: Git Exercise

After completing the to-do list application, you will need to submit your code
on a Git repository. For this part of the exercise, you will create a new
repository on GitHub (or any other Git hosting platform) and submit your code
using Git. Make sure the created repository is publicly accessible.

Here are the steps to follow:

1. Create a new repository on GitHub (or any other Git hosting platform).
1. Clone the empty repository on your local machine.
1. Move the to-do list application files into the local repository.
1. Create a .gitignore file to exclude the target directory and any other files
   that do not need to be tracked.
1. Add and commit your changes to the local repository.
1. Push your changes to the remote repository on GitHub.
1. (Optional) Create a branch for the chosen extra feature and push your changes
1. (Optional) Create a pull request proposing the changes for the chosen feature
   to be merged on your own repository main branch.
1. (Optional) Repeat the 2 previous steps for other features.

### Evaluation

Your submission will be evaluated based on the following criteria:

1. Correctness and completeness of the implementation. Does the to-do list work
   correctly and meet all of the requirements?

2. Code quality and organization. Is the code well-structured, easy to read and
   understand, and free of unnecessary complexity?

3. Use of Rust best practices and idioms. Does the code follow Rust best
   practices and idioms, and make good use of Rust language features and
   constructs?

4. Git usage. Is the Git repository well-organized and easy to navigate? Are
   commits frequent and well-documented? Is there evidence of good use of Git
   branching and merging?

## Time Limit

You should aim to complete this exercise within 4 hours. If you are unable to
complete all of the requirements within the time limit, please submit your work
as-is and include a note explaining which parts you were unable to complete and
why.

Good luck! If you have any questions, please feel free to contact us.

