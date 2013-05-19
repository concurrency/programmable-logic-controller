# plc (programmable logic controller)

*Steve Pretty 07MAR11*

**plc** is a library of software written in occam-pi, intended to be used in conjunction with the plumbing library (see [www.concurrency.cc](http://concurrency.cc/)) on the Arduino family of microcontroller boards.

**plc** aims to explore ideas for extending the functionality of the existing plumbing library. The inspiration for **plc** has been drawn from the world of programmable logic controllers as described by IEC 61131 – particularly the functional block programming model. (Note – the author has no practical experience using industrial PLCs – his primary source of reference has been the text "Programmable Logic Controllers, 5th Edition" by W. Bolton, Newnes 2009).

**plc** has been divided into 6 modules, which are outlined in the documentation directory. Each module included a number of functional blocks. The API for each functional block is fully described in the code. There is at least one test case provided for each functional block, which provides additional documentation of the intended use for each of the blocks.

**plc** is a work in progress -- more modules and functional blocks will be added over time. PLCs handle analogue signals as well as digital ones -- so that area is next on the roadmap.

# License

This code is made available under a GPL v2 license (see code). 