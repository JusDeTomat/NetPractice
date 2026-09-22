*This project has been created as part of the 42 curriculum by mbichet.*

# Description

NetPractice is a practical networking project from the 42 curriculum.
Its goal is to introduce the basics of computer networking through the
configuration of small simulated networks.

During this project, I learned how to configure IP addresses, subnet
masks, default gateways, routers, and switches in order to make network
diagrams function correctly. The project contains 10 levels, each
requiring a valid network configuration.

# Instructions

## Launching the training interface

1.  Download the project files from the project page.
2.  Extract the files into a directory.
3.  Open a terminal in that directory.
4.  Run the following command:

``` bash
./run.sh
```

The script starts a local web server and opens the training interface in
a browser.

If `run.sh` does not work, start the server manually:

``` bash
python3 -m http.server 49242
```

Then open the following address in your browser:

``` text
http://localhost:49242
```

You can use your login in the interface to access your personal
configuration, or use the **Evaluation** tab to generate a random
configuration.

## Completing the levels

-   Complete all 10 levels.
-   Modify the unshaded fields until the network configuration is
    correct.
-   Use **Check again** to verify your configuration.
-   When a level is completed, move to the next level.
-   Use **Get my config** before leaving each level to export its
    configuration.

## Submission

The repository must contain **10 exported configuration files**, one for
each level, placed at the root of the repository.

Make sure to enter your login in the training interface before exporting
the configurations.

During the defense, three random levels must be completed successfully
within a limited time. External tools are not allowed during the
evaluation, except for a simple calculator such as `bc`.

# Resources

## Networking concepts studied

This project focuses on the following networking concepts:

-   **TCP/IP addressing:** identifying devices using IP addresses.
-   **Subnet masks:** determining network and host portions of an IP
    address.
-   **Default gateways:** allowing devices to communicate with networks
    outside their local network.
-   **Routers:** connecting different networks and forwarding packets.
-   **Switches:** connecting devices within a local network.
-   **OSI model:** understanding the different layers involved in
    network communication.
-   **Network configuration:** ensuring that devices belong to
    compatible networks and can communicate correctly.

## References

- peer to peer
- [image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRJbZomRXYRVaZyqhNHgd7QL93q-QFclL6MbcJ0cECfPQHqIhOGkzdjvYNa&s=10)

## AI usage

AI was used as a learning and support tool for:

-   Clarifying networking concepts such as IP addresses, subnet masks,
    and default gateways.
-   Helping understand the logic behind network configurations.
-   Reviewing the README structure and improving its clarity.

All explanations and generated content were reviewed and checked to
ensure that I understood the concepts and could explain my work during
the peer-evaluation and defense.