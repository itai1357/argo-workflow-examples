command to deploy:
helm upgrade --install dummy-wfs . --set localEnv=true --set image.repository="localhost:5001" -n cas --create-namespace