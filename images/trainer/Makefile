VERSION=0.1
PROJECT=beacham-gke-dev

image:
	docker build -t "gcr.io/$(PROJECT)/alphago-trainer:$(VERSION)" .

push: image
	gcloud docker -- push "gcr.io/$(PROJECT)/alphago-trainer:$(VERSION)"

.PHONY: image push
