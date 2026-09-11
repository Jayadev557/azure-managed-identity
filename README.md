# Azure Managed Identity Lab

## 1. Overview

## 2. Objective

## 3. Scenario

## 4. Architecture

## 5. Lab Implementation
   ### Step 1 — Create Storage Account

Created an Azure Storage Account to store the test blob that will be accessed by the Azure VM using Managed Identity.

**Storage Account:** `milabstorage12345`

**Purpose:** Acts as the target Azure resource for the Managed Identity lab.

![Storage Account](screenshot/01-storage-account.png)

### Step 2 — Create Azure VM

Created an Ubuntu Azure Virtual Machine that represents the workload which will use Managed Identity to access Azure Storage.

**VM Name:** `mi-test-vm`

**Operating System:** Ubuntu

**Purpose:** The VM will use its Managed Identity to authenticate to Azure Storage without storing credentials.

![Azure VM](screenshot/02-vm-created.png)

### Step 3 — Enable System-Assigned Managed Identity

Enabled a System-Assigned Managed Identity on the Azure VM.

**Identity Type:** System-assigned

**Purpose:** Allows the VM to authenticate to Azure services without storing credentials such as passwords, client secrets, or storage keys.

![Managed Identity Enabled](screenshot/03-managed-identity-enabled.png)


## 6. Authentication vs Authorization

## 7. Testing and Validation

## 8. Interview Questions

## 9. Key Learnings

## 10. Cleanup

## 11. References
