# npm-stop

Execute "npm stop" inside a target_path folder.

## Requirements

This is assuming NPM is exist, without explicit dependencies.

## Role Variables

   - name: target_path
     desc: The location of the folder "npm stop" to execute.

## Dependencies

No explicit dependencies.

## Example Playbook

   - hosts: servers
     roles:
       - role: npm-stop
         target_path: "/home/ubuntu/{{ service_name }}"
