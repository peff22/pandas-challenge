# pandas-challenge

I completed most of this challenge on my own. I received general help from my groupmates Janka Glenn and Brian Keffer when I ran into a couple problems.
I also received help from Jonathan on askBCS. He provided me with the following lines of code to clear up errors I was stuck on:
school_students_passing_math = students_passing_math.groupby(["school_name"]).size()

school_students_passing_reading = students_passing_reading.groupby(["school_name"]).size()

students_passing_math_and_reading = school_data_complete[
    (school_data_complete["reading_score"] >= 70) & (school_data_complete["math_score"] >= 70)
]
school_students_passing_math_and_reading = students_passing_math_and_reading.groupby(["school_name"]).size()

I was also provided the starter code which was included with the assignment instructions.
