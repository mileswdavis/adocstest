# Aruba Campus Deployment Guide

## Introduction

Wireless has become the primary network access method for today’s fast-changing mobile environments. In the past, wireless networks were a “nice to have,” but they have evolved into a mission-critical lane for connectivity and play a major role in business continuity and employee satisfaction. In recent years, the number of connected devices per user has increased to more than three, and some estimate it will rise to as many as five per user in the next few years. Employees have their company-supplied PCs, their personal tablets, company-supplied or personal smart phones, and even their smart watches connected to the corporate Wi-Fi network. Users move between locations with their devices and require always-on access. When visiting your employees on-site, guests expect to have access to the Internet from their wireless devices. The Aruba Mobile First Campus network is designed to allow people to move while connected, securely separate employee traffic from guest traffic and to allow enterprises to innovate without being tied to a wired infrastructure. It combines the best wireless products with a resilient wired infrastructure that is ready to support mobility and Internet of Things \(IoT\) devices, as well as end-to-end network management with multi-vendor access control. Because most people work from both company-supplied and personal devices, wireless network access must be ubiquitous to accommodate the new mobile workplace. Guests want Internet access from their personal computers, tablets and smart phones, a desire that becomes a major challenge for IT departments due to the lack of control over the devices. In addition, many IoT devices connect wirelessly to today’s networks. Building control systems, card readers, thermostats, and surveillance cameras do not have users associated with them. Their traffic is considered machine-to-machine and the devices require machine authentication, which differs from user authentication. Even devices that have traditionally used wired connections, such as shared printers, copy machines, multimedia devices, and high-end workstations, are moving to the wireless world. A network with a few hundred users can easily have over a thousand connected devices.

PURPOSE OF THIS GUIDE

This guide covers the Aruba Mobile First Campus design, including reference designs along with their associated hardware and software components. It contains an explanation of the requirements that shaped the design and the benefits it will provide your organization. The guide describes a single system that integrates access points \(APs\), access switches, aggregation switches, core switches, and network management with access-control and traffic-control policies.

#### Design Goals

The overall goal is to create a simple scalable design that is easy to replicate at different sites in your network. The components are limited to a specific set of products to help with operations and maintenance. The design has a target of sub-second failover when a network device or link between two network devices becomes unavailable.

The protocols are tuned for a highly-available network in all functional areas. The design deploys link aggregation and multi-chassis link aggregation between aggregation and access devices. Routed links are utilized at the core with layer-3 path redundancy.

The guide can be used to design new networks or to optimize and upgrade existing networks. It is not intended as an exhaustive discussion of all options, but rather to present the most commonly recommended designs, features, and hardware.

Mobile First Campus Design

