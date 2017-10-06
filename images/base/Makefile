VERSION=0.1
PROJECT=beacham-gke-dev

image:
	docker build -t "gcr.io/$(PROJECT)/alphago-base:$(VERSION)" .

push: image
	gcloud docker -- push "gcr.io/$(PROJECT)/alphago-base:$(VERSION)"

.PHONY: image push
