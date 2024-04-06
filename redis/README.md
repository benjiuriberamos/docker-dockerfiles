BUILD IMAGE

docker build -t redis-dev .

### **RUN container**

docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis-dev

**ADD CLI FOR REDIS**

docker exec -it redis-stack redis-cli
