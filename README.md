# SupplyChain

**Farm Supply Chain Management****

**Introduction:**
The Farm Supply Chain Management project aims to streamline and enhance the efficiency of the agricultural product supply chain. By leveraging Hyperledger Fabric blockchain technology, this project facilitates transparent, secure, and traceable transactions from farm to consumer. The system enables farmers, distributors, and retailers to seamlessly track the journey of agricultural products, ensuring quality, authenticity, and timely delivery.

**Key Features:**

Blockchain Integration: The project utilizes Hyperledger Fabric, a permissioned blockchain framework, to maintain an immutable ledger of transactions. This ensures data integrity, security, and transparency throughout the supply chain.

Smart Contracts: Smart contracts are deployed to automate and enforce business logic within the supply chain network. These contracts define rules and actions governing the transfer of product ownership between stakeholders.

Traceability: Each agricultural product is assigned a unique identifier (productId) and accompanied by detailed information such as product description, producer details, harvest date, distribution details, and retailer information. This enables stakeholders to trace the product's journey from farm to retailer.

**Functions:**
Init Ledger: Initializes the ledger with sample farm data, demonstrating the product transfer process.
Add New Farm: Adds a new farm product to the ledger with relevant details provided by the producer.
Query Farm by Product ID: Retrieves farm product information based on the provided productId.
Change Product Ownership: Facilitates the transfer of product ownership from the producer to the distributor.
Transfer Product Distributor to Retailer: Enables the transfer of product ownership from the distributor to the retailer, completing the supply chain cycle.

**Values:**
productId: Unique identifier for each farm product. (“Aone”)
productDescription: Description of the agricultural product. (“Apple”)
producerName: Name of the farm producer. (“MahirFPO”)
producerAddress: Address of the farm producer. (“Kurnool”)
harvestDate: Date when the product was harvested. (“TenthMaytwentytwentythree”)
distributorName: Name of the product distributor. (“AndhraApple”)
distributorAddress: Address of the product distributor. (“Amravati”)
prodToDistDate: Date when the product was transferred from producer to distributor. (“twethiethMaytwentytwentythree”)
retailerName: Name of the product retailer. (“Safal”)
retailerAddress: Address of the product retailer. (“NewDelhi”)
distToRetaDate: Date when the product was transferred from distributor to retailer. (“twetyfithMaytwentytwentythree”)

**Conclusion:**
The Farm Supply Chain Management project revolutionizes agricultural supply chain operations by leveraging blockchain technology and smart contracts. By ensuring transparency, traceability, and efficiency, it fosters trust among stakeholders and enhances the quality of agricultural products reaching consumers. This system holds immense potential to optimize supply chain processes, reduce fraud, and promote sustainability in the agricultural sector.
