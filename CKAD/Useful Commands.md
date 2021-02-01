# Useful Commands / Definitions

_Imperative commands_ - on the command line rather than creating a yaml file then running that file

`--dry-run=client` - if you want to test your command before creating any resources, this will help.
`-o yaml` - This will output the resource definition in YAML format on the screen

e.g.

`kubectl run nginx --image=nginx --dry-run=client -o yaml`

- Creates a nginx pod dry run
- Outputs into a yaml format on the Terminal

`kubectl run <name> --image=<image>` - creates a pod with the name and based on an image

`kubtectl create <kubernetes-object> <name>` - creates a kubernetes object e.g. deployment, replicaset, namespace
