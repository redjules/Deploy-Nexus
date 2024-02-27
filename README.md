# Deploy Nexus

We will push a Docker repository on Nexus:

<img width="803" alt="Screenshot 2024-02-27 at 09 32 46" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/72a6e933-fd5d-48e0-8caf-0156c61b0983">

we create a repo in Nexus:

<img width="522" alt="Screenshot 2024-02-27 at 09 33 13" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/516ae691-b3c6-499f-bb4e-aca4f5b4e370">

we select mystore in Blobstore and the rest as default

<img width="546" alt="Screenshot 2024-02-27 at 09 34 05" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/df6bd109-30d1-46cd-96fe-35d1736c60cd">

we create a new role that has access to the Docker repository we created:

<img width="443" alt="Screenshot 2024-02-27 at 09 35 35" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/4acb95cf-0e6a-4c46-85f7-7272da68366a">

we give access to our user to the repo:

<img width="471" alt="Screenshot 2024-02-27 at 09 35 55" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/19e5e1ec-6282-4d24-b3a8-a28cf03dc301">

we configure a port for our Docker repo:

<img width="363" alt="Screenshot 2024-02-27 at 09 37 21" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/df07bcde-24c4-4bec-b226-94357a2a98ee">

<img width="716" alt="Screenshot 2024-02-27 at 09 38 01" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/4d495e44-fb97-4afb-9df9-38574bd08c13">

we go to firewall in a Digital Ocean droplet and put the port 8083 in inbound rules:

<img width="648" alt="Screenshot 2024-02-27 at 09 38 56" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/b70e98ff-8fe7-4734-a328-e5d113d0f2e5">

we create a Docker Realm:

<img width="708" alt="Screenshot 2024-02-27 at 09 40 18" src="https://github.com/redjules/Deploy-Nexus/assets/106017493/4f084cd9-1f78-43af-8ec4-28f55c1a13ca">

