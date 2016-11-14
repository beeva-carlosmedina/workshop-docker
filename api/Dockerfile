FROM ubuntu

MAINTAINER genDevOps

# Add binaries
ADD artifacts/* /usr/bin

# Ports
EXPOSE 8000 
# Run
CMD ["api", "--listen", ":8000"]
