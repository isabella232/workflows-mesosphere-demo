##  Wercker Workflows and Mesosphere sample application

Sample Todo application that showcases [Wercker Workflows](http://wercker.com/workflows/) in action alongside [Mesosphere](http://mesosphere.com). You can follow along with [this tutorial](http://devcenter.wercker.com/quickstarts/workflows/mesosphere.md) to set up continuous deployment to Marathon on DC/OS.

This sample application shows two Workflows. Please see the `wercker.yml` file for more details.

You can see a visual representation of the Workflows below.

![image](mesosphere-workflow.png)

## Running the app

You can run the application locally by executing the following command from the project directory (make sure you have a working Docker environment and the Wercker CLI installed):

`wercker dev --publish 3000`
