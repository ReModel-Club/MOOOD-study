# oneoneone
Modelling 111 patients with a primary care disposition

Steps to build and run

1. Create directory and place DockerFile inside it
2. cd into directory and use the command: docker build -t moood ./
3. Start the container using the comamnd: docker run -p 8080:80 moood
4. View the app at http://localhost:8080/ on your browser

Reminder to self: You can run this locally with python index.py or the model only by uncommenting line 86 in oneoneonedes.py

## Note for REMODEL participants

If you're stuck and unable to run the model, switch to the [`improve-setup-instructions`](https://github.com/ReModel-Club/MOOOD-study/tree/improve-setup-instructions) branch and try the instructions in the README there. Note that Docker required administrator permissions (e.g. sudo) so you may want to go straight to the alternative running options if you don't have admin permissions.
