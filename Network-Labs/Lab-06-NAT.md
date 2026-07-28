# Lab 06 - Network Address Translation

## Objective

Allow private addresses to access public networks.

## Commands

ip nat inside source list 1 interface g0/1 overload

## Verification

show ip nat translations

## Results

Internal hosts successfully translated to public IPs.
