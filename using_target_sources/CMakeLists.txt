add_subdirectory(fonts)
add_subdirectory(rw)

set(fruits "apple" "banana" "orange")
MESSAGE(${fruits}) # Typo will produce: message called with incorrect number of arguments
