# rtfs
RTFS is a user-friendly interface designed to assist the user in the task of building complex transmission line models for short-circuit analysis in power systems, using the Alternative Transients Program - ATP. 

This tool enables the user to carry out fault simulations with increased levels of detail, in which line spans, grounding structures, phase conductors, and shield wires are modeled and analyzed individually, allowing the construction of complex designs of long transmission lines, accounting for variations along its course (geometry and conductor changes, transpositions, soil heterogeneities) and providing direct access to current and voltage responses for all conductors at every line section.

Based on user input, RTFS writes the appropriate Line Constants blocks and main ATP files, invokes the ATP solver and processes the results according to the requested outputs. 

The main technical highlights are:

♦ Supports up to 9999 line spans.
♦ Supports Pi, Bergeron and JMarti line models.
♦ Span lenghts, soil resistivities and ground impedances may be set individually for each section or loaded from CSV files.
♦ Supports all types of faults, involving one, two and three phases, with variable incidence angle.
♦ Supports different cross-sections along the transmission line course.
♦ Supports different transposition schemes.
♦ Supports single and double circuit lines.
♦ Includes a conductor database.

External functions included:

♦ Paul Mennen (2020). prin (https://www.mathworks.com/matlabcentral/fileexchange/60981-prin), MATLAB Central File Exchange. Retrieved October 4, 2020.
