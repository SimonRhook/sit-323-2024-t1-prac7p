# sit323-2025-prac7p

Adding a Database with mongoDB

## To run

1. apply kubernetes configs:
    - `kubectl apply -f createPV.yaml`
    - `kubectl apply -f createPVC.yaml`
    - `kubectl apply -f storageClass.yaml`
    - `kubectl apply -f secret.yaml`
    - `kubectl apply -f deployment.yaml`
    - `kubectl apply -f service.yaml`
2. Connect to mongoDB using Compass `mongodb://localhost:32000`
    Ensure to add credentials in Advanced connection options
3. Create a new Database to store data
4. Add data into database
