## Project Motivation
To gain practical experience with DevOps principles through hands-on learning.

## Project Goal
Deploy [containerised Scrumblr](https://github.com/u1i/scrumblr-docker) to VM (created using Google Compute Engine)
![Screenshot 2024-04-13 at 3 30 27 AM](https://github.com/Ley94/devops-course-project/assets/25318216/22810283-42b8-4b35-bc9a-a8c6bd7b6997)

## Steps:
- Fork the [scrumblr-docker repo](https://github.com/u1i/scrumblr-docker)
- Create VM on Google Cloud Console (according to [guide](https://medium.com/@vngauv/from-github-to-gce-automate-deployment-with-github-actions-27e89ba6add8))
- Create firewall rule to allow access to port 8080 on Google Cloud Console
- Add Telegram key and Google Cloud service account id and key to repository secrets
- Create YAML file for GitHub Actions (according to [guide 1](https://medium.com/@vngauv/from-github-to-gce-automate-deployment-with-github-actions-27e89ba6add8) and [guide 2](https://github.com/u1i/ghactions-test/blob/master/.github/workflows/test1.yml))

## Screenshots:


