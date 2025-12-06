#Calculator Testing#

This project was designed as a simple yet comprehensive demonstration of how modern CI/CD pipelines ensure software quality from code writing to deployment. Using a basic calculator implementation as the main example, the repository shows how automated workflows validate functionality, ensure reliability, and maintain clean development practices.

The testing workflow was built with Python and PyTest, covering the fundamental operations of a Calculator class. Every change made to the codebase is automatically evaluated using GitHub Actions before being allowed into the main branch. This prevents the merging of faulty code and ensures the application's stability at all times.

To extend the project to real-world DevOps practices, a Docker image was also created. This image encapsulates the calculator application within a reproducible and isolated environment, demonstrating how applications can be consistently packaged for testing, distribution, or deployment. The CI pipeline automatically creates this Docker image, ensuring that the code works not only in development but also in production-like containerized environments.

##In short, this project illustrates:##

How automated unit testing ensures code correctness. How GitHub Actions evaluate each commit and pull request before merging them.

How Docker provides consistency across all environments.

How CI/CD pipelines maintain a stable and reliable software lifecycle.

This is a clear and practical example of combining Python testing, Dockerization, and continuous integration to apply engineering best practices, even in small projects.
