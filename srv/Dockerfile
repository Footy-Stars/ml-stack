FROM jupyter/minimal-notebook

# Install Python 3 packages

RUN pip install --upgrade pip \
    web3==6.9.0 \
    python-dotenv==1.0.0
    # INSTALL XGBOOST
    # Install production dependencies.

WORKDIR /home/jovyan/work
COPY requirements.txt ./
RUN pip install -r requirements.txt