# Compile the library that maintains an STM profile.
add_subdirectory(model)

# Compile the executable that creates an STM profile from a trace.
add_subdirectory(model-generator)

# Compile the executable that synthesizes a trace from an STM profile.
add_subdirectory(trace-generator)
