# Lab 04 - Access Control Lists

## Objective

Control access to network resources.

## Commands

access-list 10 permit 192.168.1.0 0.0.0.255

interface g0/0
ip access-group 10 in

## Verification

show access-lists

## Results

Traffic filtered according to ACL policy.
