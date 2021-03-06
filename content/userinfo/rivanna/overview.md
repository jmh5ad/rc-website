+++
description = ""
title = "Rivanna"
draft = false
date = "2019-06-30T17:45:12-05:00"
tags = ["hpc","rivanna","parallel-computing","supercomputer","allocations","queues","storage"]
categories = ["userinfo"]
images = [""]
author = "Staff"  
type = "rivanna"

+++

{{% callout %}}
#### Rivanna HPC

Rivanna is the University of Virginia's High-Performance Computing (HPC) system. As a centralized resource it has hundreds of pre-installed software packages available for computational research across many disciplines. Currently the Rivanna supercomputer has over 8,000 cores and 8PB of various storage.

All UVA faculty, staff, and postdoctoral associates are eligible to use Rivanna, or students when part of faculty research.
{{% /callout %}}

{{< lead >}}
The sections below contain important information for new and existing Rivanna users. Please read each carefully.
{{< /lead >}}

{{< lead >}}
New users are invited to attend one of our free orientation sessions ("Introduction to the HPC System") held throughout the year during office hours or by appointment.
{{< /lead >}}

- - -

# Get Started

<div class="card-group">
  <div class="card image-shadow col-md-5 p-3 mb-5 rounded" style="margin-right:3rem;border:solid 3px #ccc;">
    <div class="card-body">
      <h5 class="card-title">Get Access / Allocations</h5>
      <p class="card-text">Request access to Rivanna HPC for your research. Add collaborators to your project.</p>
      <a href="/userinfo/rivanna/allocations/"><button class="btn btn-primary">Request an Allocation</button></a>
    </div>
  </div>
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="border:solid 1px #ccc;"">
    <div class="card-body">
      <h5 class="card-title">Logging In</h5>
      <p class="card-text">How do you log in? Need to use a web browser or a shell command-line? Learn how.</p>
      <a href="/userinfo/rivanna/login/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
</div>

<div class="card-group">
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="margin-right:3rem;border:solid 1px #ccc;"">
    <div class="card-body">
      <h5 class="card-title">File Transfer</h5>
      <p class="card-text">How to move files? How to move large datasets to the HPC cluster? Learn how.</p>
      <a href="/userinfo/data-transfer/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="border:solid 1px #ccc;"">
    <div class="card-body">
      <h5 class="card-title">Software</h5>
      <p class="card-text">Find and run software suited for your HPC jobs. Learn how to load and use modules.</p>
      <a href="/userinfo/rivanna/software/overview/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
</div>

<div class="card-group">
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="margin-right:3rem;border:solid 1px #ccc;"">
    <div class="card-body">
      <h5 class="card-title">Storage</h5>
      <p class="card-text">Learn about the vaious storage options within Rivanna: for users, groups, and temporary.</p>
      <a href="/userinfo/rivanna/storage/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="border:solid 1px #ccc;"">
    <div class="card-body">
      <h5 class="card-title">Running Jobs in SLURM</h5>
      <p class="card-text">Your code is ready. Your data is in place. Learn how to run your jobs across the cluster, and other advanced SLURM features.</p>
      <a href="/userinfo/rivanna/slurm/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
</div>

<div class="card-group">
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="margin-right:3rem;border:solid 1px #ccc;">
    <div class="card-body">
      <h5 class="card-title">Queues</h5>
      <p class="card-text">Learn the right queue (or "partition") for running your job, such as standard, parallel, gpu, and more.</p>
      <a href="/userinfo/rivanna/queues/"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="border:solid 1px #ccc;">
    <div class="card-body">
      <h5 class="card-title">Usage Policies</h5>
      <p class="card-text">Understand what is expected of you as a Rivanna HPC user. All users must comply with these requirements.</p>
      <a href="/userinfo/rivanna/overview/#usage-policies"><button class="btn btn-warning">Learn More</button></a>
    </div>
  </div>
</div>

<div class="card-group">
  <div class="card image-shadow col-md-5 p-3 mb-5 bg-white rounded" style="margin-right:3rem;border:solid 1px #ccc;">
    <div class="card-body">
      <h5 class="card-title">FAQs</h5>
      <p class="card-text">Have a question? Others may have asked it before, so please check our Frequently Asked Questions page first.</p>
      <a href="/userinfo/rivanna/faqs/"><button class="btn btn-warning">Read our FAQs</button></a>
    </div>
  </div>
</div>

- - -

# System Details

<div id="accordion" style="margin-top:4rem;margin-bottom:4rem;">
  <div class="card">
    <div class="card-header" id="headingTwo">
      <h5 class="mb-0">
        <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo" style="text-decoration:none;color:black;font-weight:bold;">
          Queuing Policies
        </button>
      </h5>
    </div>
    <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordion">
      <div class="card-body" style="padding:1rem;">
        Rivanna is a managed resource; users must submit jobs to queues controlled by a resource manager, also known as a queueing system.  The manager in use on Rivanna is SLURM.  SLURM refers to queues as partitions because they divide the machine into sets of resources.  There is no default partition and each job must request a specific partition.  Partitions and access policies are subject to change, but the following table shows the current structure.  Note that memory may be requested per core or for the overall job.  If the total memory required for the job is greater than the number of cores requested multiplied by the maximum memory per core, the job will be charged for the additional cores whether they are used or not.  In addition, jobs running on more than one core may still require a request of total memory rather than memory per core, since memory per core is enforced by the system but some multicore software packages (ANSYS, for example) may exceed that for a short time even though they never exceed cores x memory/core.

<table class="table" style="font-weight:normal;">
  <thead class="thead-dark">
    <tr>
      <th scope="col">Partition</th>
      <th scope="col">Max time per job</th>
      <th scope="col">Max nodes per job</th>
      <th scope="col">Max cores per job</th>
      <th scope="col">Max memory per core</th>
      <th scope="col">Max memory per node per job</th>
      <th scope="col">SU Charge Rate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">standard</th>
      <th scope="row">7 days</th>
      <th scope="row">1</th>
      <th scope="row">40</th>
      <th scope="row">12GB</th>
      <th scope="row">375GB</th>
      <th scope="row">1.00</th>
    </tr>
    <tr>
      <th scope="row">parallel</th>
      <th scope="row">3 days</th>
      <th scope="row">45</th>
      <th scope="row">900</th>
      <th scope="row">6GB</th>
      <th scope="row">120GB</th>
      <th scope="row">1.00</th>
    </tr>
    <tr>
      <th scope="row">largemem</th>
      <th scope="row">4 days</th>
      <th scope="row">1</th>
      <th scope="row">16</th>
      <th scope="row">62GB</th>
      <th scope="row">975GB</th>
      <th scope="row">1.00</th>
    </tr>
    <tr>
      <th scope="row">gpu</th>
      <th scope="row">3 days</th>
      <th scope="row">4</th>
      <th scope="row">8</th>
      <th scope="row">12GB</th>
      <th scope="row">240GB</th>
      <th scope="row">2.00</th>
    </tr>
    <tr>
      <th scope="row">knl</th>
      <th scope="row">3 days</th>
      <th scope="row">8</th>
      <th scope="row">512 cores/2048 threads</th>
      <th scope="row">3 GB (per physical core)	</th>
      <th scope="row">192GB</th>
      <th scope="row">1.00</th>
    </tr>
    <tr>
      <th scope="row">dev</th>
      <th scope="row">1 hour</th>
      <th scope="row">2</th>
      <th scope="row">8</th>
      <th scope="row">6GB</th>
      <th scope="row">36GB</th>
      <th scope="row">0.00</th>
    </tr>
  </tbody>
</table>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="card-header" id="headingOne">
      <h5 class="mb-0">
        <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseOne" aria-expanded="false" aria-controls="collapseOne" style="text-decoration:none;color:black;font-weight:bold;">
          Hardware Configuration
        </button>
      </h5>
    </div>
    <div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
      <div class="card-body" style="padding:1rem;">
<table class="table" style="font-weight:normal;">
  <thead>
    <tr>
      <th scope="col">Cores/node</th>
      <th scope="col">RAM/node</th>
      <th scope="col">Nodes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">20</th>
      <th scope="row">128GB</th>
      <th scope="row">146</th>
    </tr>
    <tr>
      <th scope="row">28</th>
      <th scope="row">256GB</th>
      <th scope="row">25</th>
    </tr>
    <tr>
      <th scope="row">40</th>
      <th scope="row">384GB</th>
      <th scope="row">44</th>
    </tr>
    <tr>
      <th scope="row">16</th>
      <th scope="row">1TB</th>
      <th scope="row">5</th>
    </tr>
    <tr>
      <th scope="row">28+8 K80 GPU</th>
      <th scope="row">256GB</th>
      <th scope="row">8</th>
    </tr>
    <tr>
      <th scope="row">28+4 P100 GPU</th>
      <th scope="row">256GB</th>
      <th scope="row">4</th>
    </tr>
    <tr>
      <th scope="row">28+4 V100 GPU</th>
      <th scope="row">256GB</th>
      <th scope="row">1</th>
    </tr>
    <tr>
      <th scope="row">64 Knight's Landing</th>
      <th scope="row">196GB</th>
      <th scope="row">8</th>
    </tr>
  </tbody>
</table>
      </div>
    </div>
  </div>
<!--
  <div class="card">
    <div class="card-header" id="headingThree">
      <h5 class="mb-0">
        <button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree" style="text-decoration:none;color:black;font-weight:bold;font-size:110%;">
          Storage Options
        </button>
      </h5>
    </div>
    <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordion">
      <div class="card-body" style="padding:1rem;">
      <p>A more complete description of storage options and policies is at our <a href="/userinfo/rivanna/storage/">HPC storage page</a>.</p>
      <h4>Home Directories</h4>
      <p>Each user has a home directory.  This storage is accessed as <code>/home/$USER</code>, where <code>$USER</code> is an environment variable set by the system that corresponds to the user's login ID.</p>
      <p>The <code>hdquota</code> command shows usage of space for the home directory only.</p>
      <h4>Scratch Storage</h4>
      <p>All nodes share a high-speed Lustre filesystem for temporary storage with up to 1.4PB of storage space for all users.   Each user is assigned space with a default quota of 10TB of storage per user.   This storage is accessed as <code>/scratch/$USER</code>.</p>
      <h4>Long-Term Storage</h4>
      <p>Groups may lease permanent storage from ITS which can be mounted to Rivanna.</p>
      </div>
    </div>
  </div>
  -->
</div>

- - -

# Usage Policies

Research computing resources at the University of Virginia are for use by faculty, staff, and students of the University and their collaborators in academic research projects.  Personal use is not permitted.  Users must comply with all University policies for access and security to University resources.  The HPC system has additional usage policies to ensure that this shared environment is managed fairly to all users. UVA's Research Computing (RC) group reserves the right to enact policy changes at any time without prior notice.

## Frontends

Exceeding the limits on the frontend will result in the user’s process(es) being killed. Repeated violations will result in a warning; users who ignore warnings risk losing access privileges.

## Standard Partition

Each job in the standard queue is restricted to a single node. Users may submit multiple jobs or job arrays, but the maximum aggregate cpu cores allowed for a single user’s running jobs is 1000.

## Parallel Partition

Users must request a minimum of two nodes and four cpu cores (and no more than 900 cpu cores) when submitting a job to the parallel queue.

## Software Licenses

Excessive consumption of licenses for commercial software, either in time or number, if determined by system and/or RC staff to be interfering with other users' fair use of the software, will subject the violator's processes or jobs to termination without warning.  Staff will attempt to issue a warning before terminating processes or jobs but inadequate response from the violator will not be grounds for permitting the processes/jobs to continue.

## Inappropriate Usage

Any violation of the University’s security policies, or any behavior that is considered criminal in nature or a legal threat to the University, will result in the immediate termination of access privileges without warning.

<br clear=all />
