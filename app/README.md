# Carbon Tracker

---

## Name

Carbon (CO2) / Power usage tracker

## Description

This repository provides a comprehensive solution for tracking the environmental impact of machine learning (ML) applications. Designed to offer insights into the power usage and carbon dioxide emissions associated with training and inference processes, it encompasses a Client, a Server, a connected Database, and a dashboard for visualizing the results.

## Architecture

1. Client: The Client component serves as the interface through which users interact with the Carbon Tracker system. Users can submit their ML code for analysis, specifying parameters such as the training dataset, inference workload, and hardware configuration.

2. Server: The Server component acts as the central processing unit of the Carbon Tracker system. Upon receiving input from the Client, it orchestrates the execution of ML tasks, monitors resource consumption, and calculates associated carbon emissions. The Server is responsible for managing the interaction between various system modules and ensuring smooth operation.

3. Database: The connected Database serves as the repository for storing relevant data generated during the tracking process. This includes information such as power usage metrics, carbon emissions estimates, hardware specifications, and execution times. The Database facilitates data retrieval for subsequent analysis and visualization.

4. Dashboard: The resulting dashboard provides users with a graphical representation of the environmental impact of their ML applications. Through intuitive visualizations, users can gain insights into the energy consumption, CO2 emissions, and runtime performance of their algorithms. The dashboard enables users to make informed decisions regarding optimization strategies and resource allocation.s

## Functionality

1. Tracking ML Workloads: The Carbon Tracker system tracks both the training and inference phases of ML applications. It captures resource utilization metrics such as CPU/GPU usage for a varying number of computing units.

2. Carbon Emission Estimation: By correlating resource usage data with corresponding carbon emission factors, the system calculates the environmental impact of ML tasks. This includes estimating the amount of CO2 emissions generated during the execution of algorithms, as well as comparing the execution times.

3. Customization and Scalability: The Carbon Tracker repository offers flexibility for customization according to user requirements and supports scalability to accommodate varying workload sizes and hardware configurations.

## Installation

Installing using pip: pip install carbontracking

Cloning using git clone

## Usage

Usage is displayed in following colab notebook:
https://colab.research.google.com/drive/1AsMpi_7Tdr8Rmd2oFDK5qvPyLJl5XH6W?usp=sharing

## Support

Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap

If you have ideas for releases in the future, it is a good idea to list them in the README.

## Authors and acknowledgment

Show your appreciation to those who have contributed to the project.