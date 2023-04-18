# Automate-Nexus-Deployment

Automate Nexus deployment on a remote CentOS7 machine

- Requirements:</br>
  Nexus node:</br>
    ❏ Minimum 1 VCPU & 2 GB Memory</br>

- The yaml file consists of three plays:</br>
  ❏ First Play “Install java and net-tools”</br>
  ❏ Second Play “Download and unpack Nexus installer”</br>
  ❏ Third Play “Create nexus user to own nexus folders</br>
  ❏ Fourth Play “Start nexus with nexus user”</br>
  ❏ Fifth Play “Verify nexus running”
