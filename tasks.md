# python-build-cli-planner-app

## Task one

One way to implement abstract base classes in Python is to use a regular class, and have each class method throw a NotImplementedError exception. This ensures that subclasses override the abstract methods.

In the file `src/regular_reminder.py`, create a class named `RegularReminder` with two class methods; `__iter__(self):` and `__str__(self):`, both raising `NotImplemenetedError` exceptions