ARG version
FROM almalinux:${version:-9}
 ENV course="devops" \
     duration="120hrs" 
 ARG trainer="mohan" 
 ENV trainer=$trainer
 RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}"
 CMD ["sleep", "1000"]