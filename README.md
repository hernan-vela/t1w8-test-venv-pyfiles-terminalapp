# t1w8-test-venv-pyfiles-terminalapp

## Virtual Envoironments
- They help create isolated environments for your projects, ensuring each project has its own dependencies.

## Testing
- Allows us to confirm whether the applicaiton works as intended or not.
- Helps catch bugs early and ensure that your code behaves smoothly.

### Types of Testing
- Manual vs Automates

    - Manual: When a person manually performs tasks, based on events.
    - Automate: Programmed tests, also called scripts, to automatically perform tasks without human envolvement.

- Unit testing: Testing specific components/functions/methods
- Integration testing: Testing the compatibility with other modules/packages.
- Chaos testing: Making a program break on purpose by disabling a functon or feature to see how errors are handled.
- Stress testing: Testing in high volumen of data/inputs (depending on use-case).
- End to end / Acceptance testings: Testing done towards the end of the project when is almost complete, to ensure things work effectively.

Note: Great ides to organise your directory structure for maintenance and easy access.

## pytest
- Power and user-friendly testing framework
- Simple yet powerful.
- pytest follows the principle of 'assert'-ing that things are true in order for a test to pass.
- For a test to pass, the assert value must be true.

- Reading test output: "." means pass, "F" means failed, "E" means exceptions

### Exceptions
- Used to check what happens when things go wrong.
- How your program is handled when things go wrong.

### Parameterized tests
- Might want to test the same function with multiple inputs.
- Parameterize creates different test cases for all the inputs provided.
- Make sure you initialize the packages to use them in other folders.
