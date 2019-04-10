# RcCarProject

This project has 1 goal:
  to learn c++ in the context of embedded software architecture.

The project will have multiple phases:

  Initial Ideation:
    first a basic diagram will be drawn, then tests will be written in gtest
    then a basic implementation using an event loop in c++ with emulated wireless connections. So that both software projects can be tested under 1 environment.

  Phase 2:
    tested fw is put onto 2 networked devices, and the current thought is to have them talk over a public redis server on the car which should also host a wifi accespoint.

  Phase 3:
    actual hardware will be bought and assembled to make  a physical layer.
    this will require lowlevel driver design in c++.

  Phase 4:
    expand the architecture to using threads to handle sensor data, motor control, battery monitoring and data transmission.

  Phase 5:
    make a video on the different phase and try to present the project somewhere.
