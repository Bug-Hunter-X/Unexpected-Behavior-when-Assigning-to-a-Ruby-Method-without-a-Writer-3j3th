# Ruby Unexpected Assignment Behavior

This repository demonstrates a subtle bug in Ruby related to assigning values to methods without explicit writer methods.  When a method is defined using `attr_reader` or without a corresponding `attr_writer` or explicit setter method, assigning a new value to it does not modify the object's internal state.  This can lead to unexpected results if not carefully considered.

The `bug.rb` file shows the problematic code, and `bugSolution.rb` provides the corrected implementation.
