# tagls

Lists the available tags of a container image from a remote registry.

IMHO this feature is missing from the docker command itself. Running it with a container image specified as an argument simply shows you all of the available tags for that image.

This script also supports (most) custom registries, like quay.io.

Examples:

List all tags for ubuntu on dockerhub: `tagls ubuntu`

List all tags for ubuntu that contain "18.04": `tagls ubuntu 18.04`

List all tags for an image on a custom registry: `tagls quay.io/coreos/clair`
