# Welcome to the rule checker.

The rule checker is tool that will allow one to create a set of rules defining
the behaviour of a system. A rule is basically desribing a set of conditions
that should be met for this rule to be valid. The conditions of rules are
subject to changes depending on the system configuration. For instance, a car
may be limited to 90 Km/h and a bus limited to 60 Km/h on the very same road.

The system configuration will define a theoritical system (model) that will be
run against the rules and produce an expected results. The real system
(implementation) will run the same rules and produce results.

As the system configuration is the same for both the model and the
implementation, the results have to be equals.

In general, the goal is be to test the functional behaviour of a device, like a
black box of a finished system. 


## Hello World example

In this example, a Hello world rule will be created and tested against different
"systems".

The rule could expect different entry, such as a GUI interface displaying the
value to a simple console.

For the time being, there will be only configuration set to console mode UTF8.
The implementation will running on  bash/python/c/cpp.
