# MAX274 2nd, 4th, 6th and 8th Order Filters.

The MAX274 is continuous-time active filter consisting of independent cascadable 2nd-Order sections.

 It comprises four 2nd-order section.


I have worked on the implementation of BandPass and LowPass filters of several orders 2nd, 4th, 6th and 8th.

Firstly, I started with reading the Datasheet of MAX274 to understand how things work. To achieve the goal which it is a filter with a Bandwidth = [18Khz, 22Khz] and a maximum Gain in this Bandwidth, for that we need to calculate first the external values of the components and choose the best fit of the center frequency and quality factor.
