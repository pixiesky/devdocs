---
layout: default
group: test-guide
subgroup: B1_Running_Integration_Tests
title: Running Integration Tests
menu_title: Running Integration Tests
menu_node: parent
contributor_name: Vinai Kopp
contributor_link: http://vinaikopp.com/
github_link: test/intgration/integration_test_execution.md
---

## Running integration tests

* TOC
{:toc}

Integration tests require the Magento runtime environment, so they need a little preparation before they can be executed. After preparation, the tests can be executed using either the command line interface or in an IDE like PHPStorm.

### Setting up the integration test framework
To run the integration tests, you must configure a test database.  Besides this, you might also want to adjust the PHPUnit configuration, depending on your requirements.

Please refer to [Preparing integration test execution]({{ site.gdeurl }}test/integration/integration_test_setup.html) for further information on setting up the test environment.

### Command Line Interface (CLI)  

This option can be used for running the tests locally during development or on remote servers during Continuous Integration.  

Please refer to [Running integration tests in the CLI]({{ site.gdeurl }}test/integration/integration_test_execution_cli.html) for further information.

### PHPStorm IDE

Running the integration tests in an IDE like PHPStorm IDE is convenient during development. This is mostly used when writing a new integration test.

Other then convenience, there is no benefit over running the tests on the console.

Please refer to [Running integration tests in PHPStorm]({{ site.gdeurl }}test/integration/integration_test_execution_phpstorm.html) for further information.
