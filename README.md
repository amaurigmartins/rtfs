# rtfs
RTFS is a user-friendly interface designed to assist the user in the task of building complex transmission line models for short-circuit analysis in power systems, using the Alternative Transients Program - ATP. Based on user input, this helper tool writes the appropriate Line Constants blocks and main ATP files, invokes the ATP solver and processes the results according to the requested outputs. The main technical highlights are:

- Supports up to 9999 line spans.
- Supports Pi, Bergeron and JMarti line models.
- Span lenghts, soil resistivities and ground impedances may be set individually for each section or loaded from CSV files.
- Supports all types of faults, involving one, two and three phases, with variable incidence angle.
- Supports different cross-sections along the transmission line course.
- Supports different transposition schemes.
- Supports single and double circuit lines.
- Includes a conductor database.
