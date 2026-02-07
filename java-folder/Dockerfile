# Use official OpenJDK image
FROM openjdk:17-slim

# Set working directory
WORKDIR /app

# Copy Java file
COPY 2largest.java .

# Compile Java file
RUN javac 2largest.java

# Run program
CMD ["java", "2largest"]

