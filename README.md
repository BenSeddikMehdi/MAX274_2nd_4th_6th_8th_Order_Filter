# MAX274 2nd, 4th, 6th and 8th Order Filters.

The MAX274 and MAX275 are continuous-time active filters consisting of independent cascadable 2nd-order sections. Each section can implement any all-pole bandpass or lowpass filter response, such as Butterworth, Bessel, Chebyshev, and is programmed by four external resistors. The MAX274/MAX275 provide lower noise that switched-capacitor filters, as well as superior dynamic performance—both due to the continuous-time design. Since continuous-time filters do not require a clock, aliased and clock noise are eliminated with the MAX274/MAX275.

I have worked on the implementation of BandPass and LowPass filters of several orders 2nd, 4th, 6th and 8th.

Firstly, I started with reading the Datasheet of MAX274 to understand how things work. To achieve the goal of building a filter with a Bandwidth = [18Khz, 22Khz] and a maximum Gain at this Bandwidth, first we need to calculate the external values of the components and choose the best fit of the center frequency and quality factor and collect them.

Once we done with 2nd-Order filter we duplicate it 3 times, and connect them in Cascade Mode to obtain the filter of 8th-Order.

# By El Mehdi BEN
