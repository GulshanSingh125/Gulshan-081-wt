# Use official GCC image
FROM gcc:latest

# Set working directory inside container
WORKDIR /app

# Copy C++ file into container
COPY twosum.cpp .

# Compile the C++ program
RUN g++ twosum.cpp -o twosum

# Run the executable
CMD ["./twosum"]

