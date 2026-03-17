
# Exploring-package.json-in-Node.js

## Dependencies and DevDependencies

Dependencies in node.js are packages that need to be added for production cases to work and any user using it needs to have it. DevDependencies is used for troubleshooting and derveloping within node.js and only should be used by the developers. While there are some overlaps for each there are more testing tools you will only see in devDependencies.

---

## Versioning

Versioning is extremely important when working with multiple input packages especially when updating or running on a beta version. Running non stable channel versions can cause these packages to crash and not work correctly with little to no troubleshooting information given. Always check what is the oldest and newest version of all conjoined packages before adding anythign new in or making sure you have backups before changing anything.

---

## Repository

The repository fielod can help you remember where this code should be stored or can be used to help automate updates with github or git.

---

## package-lock.json

package-lock.json is a locked file that records and organizes information about the install npm that you used and all the infomration that needs to go with it. including all versions, dependancies, integrities, and resolved URL's
