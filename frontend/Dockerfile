- name: Build and push frontend
  uses: docker/build-push-action@v4
  with:
    context: ./frontend
    file: ./frontend/Dockerfile
    push: true
    tags: ${{ secrets.DOCKERHUB_USERNAME }}/fusionpact-frontend:latest
