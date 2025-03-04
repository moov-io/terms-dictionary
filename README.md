# Dictionary of key terms and acronyms

Below are some simple definitions of terms, acronyms, companies, and projects related to financial services and Moov. This is not a complete list, so please feel free to submit a pull request adding a new term with a definition!

## Table of Contents
- [Banking and Payments](#banking-and-payments)
- [Sales](#sales)
- [Software and Technology](#software-and-technology)
- [ACH SEC Codes](#ach-standard-entry-class-codes)
- [Moov's Open Source Projects](#moovs-open-source-projects)

## Banking and Payments

- **1099**<a id="1099"></a>: A 1099 usually refers to the IRS 1099-NEC form (formerly 1099-MISC). Each year, it’s sent to independent contractors and freelancers (non-employees) who have been paid $600 or more by a client company. Separate 1099s are sent for each company.

- **A2A (Account-to-Account)**<a id="a2a"></a>: Payments that involve the transfer of funds between two accounts owned by a single party. These accounts may be at the same or different financial institutions.

- **accounts payable (AP)**<a id="ap"></a>: Amounts due to vendors or suppliers for goods or services received that have not yet been paid for.

- **accounts receivable (AR)**<a id="ar"></a>: Amounts owed for goods or services delivered that have not yet been paid for.

- **ACH (Automated Clearing House)**<a id="ach"></a>: A U.S. network that coordinates electronic payments and automated money transfers. ACH is a way to move money between banks without using paper checks, wire transfers, card networks, or cash.

- **ACH authorization**<a id="ach-authorization"></a>: An originator must obtain authorization from a receiver to originate one or more entries to the receiver’s account.

- **ACH credit**<a id="ach-credit"></a>: A transaction pushing funds into an account (e.g., payroll direct deposit).

- **ACH debit**<a id="ach-debit"></a>: A transaction pulling funds from an account (e.g., monthly mortgage payment).

- **ACH return**<a id="ach-return"></a>: A credit or debit entry initiated by an RDFI or ACH Operator that returns a previously originated credit or debit entry to the ODFI within the time frames established by NACHA rules.

- **ACH reversal**<a id="ach-reversal"></a>: A credit or debit entry that reverses an erroneous entry. Must be transmitted to or made available to the RDFI within five banking days following the settlement date of the erroneous entry.

- **acquirer / acquiring bank**<a id="acquirer"></a>: A financial institution that processes payment transactions, such as credit or debit card payments, on behalf of a merchant. In the payments value chain, the Acquirer enables businesses to accept credit card payments for the purchase of goods and services. The Acquirer underwrites the merchant account, and may provide hardware and software to enable the merchant to process transactions.

- **acquiring**<a id="acquiring"></a>: The process whereby a bank or financial institution (also known as acquiring bank or acquirer) processes credit or debit card transactions on behalf of a merchant, enabling that merchant to accept card payments for the purchase of goods and services.

- **addenda record**<a id="addenda-record"></a>: An ACH record that contains supplemental data related to an ACH entry. This information may be needed to completely identify an account holder or provide information concerning a payment to the RDFI and receiver.

- **address verification service (AVS)**<a id="avs"></a>: A security service that checks the street address and zip code against the data on file with the issuer at the time of a card not present transaction. Certain responses may result in declines and lack of information could affect interchange rates.

- **AFT (Account Funding Transaction)**<a id="aft"></a>: A card network transaction used to pull funds from a payment card in order to fund an account balance (e.g. wallet, card, prepaid card) or fund a push payment to another party.

- **anti-money laundering (AML)**<a id="aml"></a>: The process of preventing, detecting, and reporting money laundering, which is the illegal process of making money with criminal origins seem like it was obtained legitimately.

- **approval**<a id="approval"></a>: (For card transactions) A response during the authorization attempt that indicates the card is valid and the transaction amount is secured for the requesting merchant until the transaction is either reversed, the approval expires or is captured and settled.

- **arbitration**<a id="arbitration"></a>: The process utilized by credit card issuing companies to ascertain whether an acquirer has definitive responsibility for a chargeback.

- **ATM (Automated Teller Machine)**<a id="ATM"></a>: A specialized computer that allows users to check account balances, withdraw or deposit money, view account activity, and possibly make purchases.

- **B2B (Business-to-Business)**<a id="b2b"></a>: Payments between two businesses, for example, between a manufacturer and retailer. Unlike in [B2C](#b2c), products and services are not for personal use, are usually sold in bulk, and often involve private price negotiations.

- **B2B2B (Business-to-Business-to-Business)**<a id="b2b2b"></a>: A model where a business indirectly sells to another business through a middleman. This is similar to [B2B](#b2b), but adds an extra link (e.g., manufacturer to wholesaler to retailer).

- **B2B2C (Business-to-Business-to-Consumer)**<a id="b2b2c"></a>: A model where a business accesses the consumer market through another business (indirect distribution). (e.g., IT services to bank to bank's customers)

- **B2C (Business-to-Consumer)**<a id="b2c"></a>: Also known as direct-to-consumer, this refers to selling products and services directly to customers without a middleman.

- **bank identification number (BIN)**<a id="bin"></a>: The initial four to six digits that appear on a payment card, identifying the bank or entity that issued the card, that issuer’s location, and the card type (e.g., credit, debit, gift). A BIN may also be referred to as an issuer identification number (IIN).

- **bank identifier code (BIC)**<a id="bic"></a>: Also known as a SWIFT code, this is an 8-11 character code that identifies a bank’s location and particular branch for international transfers.

- **Bank Secrecy Act (BSA)**<a id="bsa"></a>: Also referred to as The Currency and Foreign Transactions Reporting Act, this [anti-money laundering (AML)](#aml) act combats criminal activity by requiring financial institutions to assist the U.S. government by keeping certain records and reporting suspicious activity such as large cash transactions.

- **basis point (BP)**<a id="bp"></a>: Equivalent to 0.01%, it’s used to reduce ambiguity when defining percentage change. For example, an increase in 150 basis points from 2% gives you 3.5%.

- **batch**<a id="batch"></a>: The accumulation of captured (sale) transactions waiting to be settled. Multiple batches may be settled throughout the day.

- **beneficial owner**<a id="beneficial-owner"></a>: An individual who ultimately owns or controls more than 25% of a company’s shares or voting rights.

- **business day**<a id="business-day"></a>: Any day that is not a weekend or a holiday where the Federal Reserve is closed. This term is often used in defining the timeline of a payment transaction, such as the number of days that will expire before funds will be deposited in an account after a transaction is initiated.

- **C2B (Consumer-to-Business)**<a id="c2b"></a>: A form of commerce that involves consumers providing a product or service to businesses. This is a rapidly growing model and often takes the form of brand sponsorships on social media.

- **C2C (Consumer-to-Consumer)**<a id="c2c"></a>: Payments that involve the transfer of funds between two different consumer accounts for goods or services, often through an online marketplace like eBay, Etsy, or Craigslist.

- **capture date**<a id="capture-date"></a>: The date an authorization is secured and prepared for movement by an acquirer on behalf of a merchant.

- **card present**<a id= "card-present"></a>: Payment card transactions where the physical card is present at the point of transaction and is entered using chip technology, the magstripe or NFC methods.

- **card not present (CNP)**<a id="cnp"></a>: Payment card transactions where the physical card is not present at the point of transaction, such as online purchases.

- **card verification code (CVC/CVV/CSC/CVD/CID)**<a id="card-verification-code"></a>: A security code added to a payment card for use during the authorization process. The purpose of the CVC is to verify that the cardholder making the transaction during a card-not-present transaction actually possesses the credit or debit card being used for the purchase. Credit card companies have their own name for the code. For Visa and MasterCard, the code appears as three digits on the back of the card. For American Express, the verification code appears as four digits on the front of the card.

- **cash advance**<a id="cash-advance"></a>: An amount of cash advanced by a bank teller or ATM to a bank cardholder that is drawn against the cardholder’s line of credit.

- **Central Bank Digital Currency (CBDC)**<a id="cbdc"></a>: A digital form of a country's fiat currency issued by the central bank. Unlike cryptocurrencies, CBDCs are regulated and centralized.

- **challenger bank**<a id="challenger-bank"></a>: Also called a neobank, this is a small, new, fully-digital bank that typically offers a mobile app and charges low fees. Neobanks aim to avoid the complexity of traditional banking and may partner with a licensed financial institution or be licensed themselves.

- **chargeback**<a id="chargeback"></a>: A reversal of funds initiated by a card issuer made to a merchant.  Reasons for chargebacks may include but are not limited to fraud, goods/services not received and items not as described.

- **check/cheque**<a id="check"></a>: A document that orders a bank to pay a specific amount of money from a party’s account to another party whose name the check has been issued.

- **Check 21 Act**<a id="check-21"></a>: A federal law that allows banks to create equivalent electronic images of paper checks for faster processing. The process of creating a check image is called "check truncation", while the electronic copy itself is called a "substitute check" or "image cash letter (ICL)".

- **checking account**<a id="checking-account"></a>: Allows for easy access to funds and often comes bundled with a debit card and checks. No minimum balance is required. Also called a demand deposit account (DDA).

- **check verification**<a id="check-verification"></a>: A database service provided to merchants, businesses, and individuals to verify a check writer has a valid checking account and does not have a history of writing bad checks. This is not a guarantee of payment to the merchant.

- **CHIPS (Clearing House Interbank Payments System)**<a id="chips"></a>: Owned by [The Clearing House](#tch), this is a private-sector alternative to [Fedwire](#fedwire) that clears payments on a net basis and is less expensive than Fedwire.

- **clearing**<a id="clearing"></a>: The process for reconciling a financial transfer by exchanging transaction details. This process provides a layer of protection for all parties involved in a transaction by recording financial details and validating the availability of funds.

- **closed-loop payment system**<a id="closed-loop"></a>: Closed loop payment systems operate without intermediaries, where the end parties have a direct relationship with the payments system.

- **commercial card**<a id="commercial-card"></a>: A generic term referring to payment cards issued to businesses for use by employees to cover expenses (e.g., corporate cards, business cards, and purchase cards).

- **counterparty**<a id="counterparty"></a>: The entity on the opposite side of any financial transaction.

- **credit bureau**<a id="credit-bureau"></a>: A company that collects, researches, and maintains credit information, and sells that data to lenders, creditors, and consumers as credit reports. Though there are many credit bureaus, the most recognizable are Equifax, Experian, and TransUnion.

- **credit card**<a id="credit-card"></a>: A plastic or virtual card with a credit limit used to purchase goods and services and to obtain cash advances on credit for which a cardholder is subsequently billed by the [issuer](#issuer) for repayment of the credit extended.

- **credit transaction (unmatched)**<a id="credit-transaction"></a>: A transaction that gives money back to the cardholder without an existing offsetting sale. Similar to a refund, a credit transaction results in money being moved from the merchant to the cardholder and interchange fees may be applied.

- **card authorization**<a id="credit-card-authorization"></a>: The initial electronic request made by a merchant to verify a specific amount is available on a card. This process confirms if a card is valid and has adequate funds to cover a transaction. See "decline" and "approval" for the different authorization responses.

- **credit score**<a id="credit-score"></a>: A three-digit number that represents how likely a person is to pay back a loan based on their payment history. A higher score is better.

- **currency transaction report (CTR)**<a id="ctr"></a>: A report that U.S. financial institutions are required to file for transfers greater than $10,000 as part of the [Bank Secrecy Act](#bsa).

- **customer identification program (CIP)**<a id="cip"></a>: Financial institution procedures for proper [KYC](#kyc)/[KYB](#kyb) vetting. Required by the 2003 USA Patriot Act.

- **debit**<a id="debit"></a>: A charge to a customer’s deposit account.

- **debit card**<a id="debit-card"></a>: A plastic or virtual card used to purchase goods and services, where payments are made directly from the cardholder's checking account.

- **declined**<a id="declined-card"></a>: (For card transactions) A response during the authorization attempt that refers to the refusal of a credit card issuer to authorize and proceed with a payment transaction. A decline can occur for several reasons, including the suspicion of fraudulent activity, account-balance deficiency, a new card that has yet to be activated, etc.

- **digital wallet**<a id="digital-wallet"></a>: Also known as an eWallet, this refers to a software application usually used in conjunction with a mobile payment system to facilitate electronic payments using a computer or smartphone for online transactions as well as purchases at physical stores. Digital wallets need to be linked to the user’s bank account.

- **discount rate**<a id="discount rate"></a>: The percentage fee paid by merchants associated with accepting card payments. This could be a standalone rate or a rate added on top of interchange.

- **dispute**<a id="dispute"></a>: A dispute arises when a cardholder formally questions the validity of a payment by raising a complaint to their card issuer. If the dispute is successful, the card issuer will process a [chargeback](#chargeback), reversing the payment so the cardholder can get their money back.

- **doing business as (DBA)**<a id="dba"></a>: This term refers to a secondary name (also known as an assumed name, fictitious business name, or trade name) that is legally associated with a company and can be used to open bank accounts, write checks, enter into contracts, and for other business purposes. That company must lawfully file this secondary name or faces fines and penalties. A sole proprietor is usually required to file for a DBA, while for large organizations with multiple businesses and brands, a DBA helps identify the true ownership, for legal purposes.

- **Data Security Standard (DSS)**<a id="dss"></a>: Also referred to as the Payment Card Industry Data Security Standard (PCI DSS), this is a common set of information security policies and procedures for use by entities that handle credit card data (basically, any organization that accepts, processes, stores, or transmits credit card information) to protect that data and prevent misuse of cardholders’ personal information.

- **electronic funds transfer (EFT)**<a id="eft"></a>: Electronic transfer of money from one bank account to another, either within a single financial institution or across multiple institutions, via computer-based systems without the direct intervention of bank staff.

- **Electronic Benefits Transfer (EBT)**<a id="ebt"></a>: The electronic system enabling government assistance programs to issue benefits to recipients in the form of payment cards, or EBT cards. Previously, state welfare agencies distributed benefits in the form of paper coupons.

- **EMV (Europay, Mastercard, and Visa)**<a id="emv"></a>: Payment card technology that uses a chip to transmit data securely. EMV cards may be contact or contactless, and are a way to reduce card fraud. EMV is the preferred way of accepting card present transactions to reduce merchant liability.

- **Electronic Payments Network (EPN)**<a id="epn"></a>: Owned by The Clearing House and one of two ACH operators (the other is the Federal Reserve Bank). The EPN is responsible for ACH transaction switching among banks for the private sector.

- **End-to-End (E2E)**<a id="e2e"></a>: The management of a financial transaction from beginning to end. This includes initiation, processing, verification, and settlement.

- **faster payments**<a id="faster-payments"></a>: An umbrella term for payment solutions that are always available, offer immediate funds availability, and provide near-instant updates to both the sender and receiver. Examples include [RTP](#rtp) and [FedNow](#fednow).

- **FinCEN (Financial Crimes Enforcement Network)**<a id ="fincen"></a>: A bureau of the United States Department of the Treasury focused on safeguarding the financial system from illicit use through the collection and analysis of financial transactions.

- **FedNow**<a id="fednow"></a>: A real-time gross settlement system that offers immediate access to funds once a payment message is received. Planned to release in 2024, FedNow is similar to [Fedwire](#fedwire), but designed for smaller transactions and with better availability. FedNow is also the publicly-owned counter to The Clearing House's [RTP](#rtp) network.

- **Fedwire**<a id="fedwire"></a>: A real-time gross settlement funds transfer system operated by the U.S. Federal Reserve Banks that allows financial institutions to electronically transfer funds. Transfers can only be initiated by the sending bank once they receive the proper wiring instructions for the receiving bank. These instructions include: the receiving bank's routing number, account number, name, and dollar amount being transferred. This information is submitted to the Federal Reserve via the Fedwire system. Once the instructions are received and processed, the Fed will debit the funds from the sending bank's reserve account and credit the receiving bank's account. Wire transfers sent via Fedwire are completed the same business day, with many being completed instantly.

- **foreign exchange (forex, FX)**<a id="foreign-exchange"></a>: See [money service business](#money-service-business).

- **funding source**<a id="funding-source"></a>: Any financial institution, bank, or other funding entity providing liquidity to accommodate various payment flows.

- **good funds**<a id="good-funds"></a>: Funds considered equivalent to cash and guaranteed to be available upon demand.

- **gatway service provider (GSP)**<a id="gsp"></a>: A gateway service provider is a third party that provides gateway services.  Typically facilitating communications between a [PSP](#psp) and an [acquirer](#acquirer).

- **hold**<a id="hold"></a>: When a final transaction total is uncertain, as in a hotel stay, an authorization hold is placed on a portion of the cardholder’s credit limit or debit balance as a pledge of collateral. Once the full amount of the transaction is determined, usually at checkout, the card is charged and the hold is removed.

- **idempotency**<a id="idempotency"></a>: A property that prevents the replication of transfers in the case of unintended repeated submissions.

- **image cash letter (ICL)**<a id="icl"></a>: See [Check 21](#check-21).

- **independent sales organization (ISO)**<a id="iso-sales"></a>: In merchant services, this refers to a third-party payment processing company, often an approved entity reselling services from banks, payment processors, or other large financial institutions.

- **instant account verification (IAV)**<a id="instant-account-verification"></a>: An account ownership verification tactic where a user provides credentials for their financial institution, and an automated process signs in on their behalf to retrieve account information. See also [micro-deposit](#micro-deposit).

- **interchange fee**<a id="interchange"></a>: In credit card processing, this refers to the fees paid by the acquiring bank to the issuing bank to compensate for transaction-related costs. Card networks like Visa and Mastercard establish interchange fees, which are impacted by multiple variables including (but not limited to) card type (debit or credit), merchant type, entry method (card present vs. card not present), and data passed at the time of the transaction (e.g. zip code).

- **international bank account number (IBAN)**<a id="iban"></a>: An alphanumeric code composed of up to 34 characters that identifies an individual account in an international transaction.

- **International Organization for Standardization (ISO)**<a id="iso-standards"></a>: An international standard setting organization involved in everything from food safety to financial services. As ISO puts it, a standard is "a formula that describes the best way of doing something". Notable financial standards are ISO 8583 and ISO 20022.

- **issuer / issuing bank**<a id="issuer"></a>: A financial institution, such as a bank or a credit union, which offers a payment card (credit or debit cards) directly to consumers (or organizations) and is liable for the use of the card. The issuer is also responsible for the billing and collecting of funds for purchases that were made using that card. In the payments value chain, the card issuer pays the acquiring bank for purchases of goods and services made by the cardholder. The cardholder then repays the issuing bank based on terms of an existing agreement.

- **issuer processor**<a id="issuer processor"></a>: A financial/technological intermediary that connects to card networks and issuing banks to provide a way to authorize transactions and manage financial records, settlement, and card issuing.

- **issuer identification number (IIN)**<a id="iin"></a>: See [BIN](#bin).

- **joint account**<a id="joint-account"></a>: An account co-owned by two or more parties, who all have equal responsibilities and permissions.

- **KYB (Know Your Business)**<a id="kyb"></a>: See [KYC](#kyc).

- **KYC (Know Your Customer)**<a id="kyc"></a>: A standard banking risk assessment practice to prevent identity theft, money laundering, fraud, and terrorism by verifying customer identities and understanding their transaction habits. KYC is a mandatory requirement of legal compliance in the financial sector.

- **ledger**<a id="ledger"></a>: A book in which the monetary transactions of a business are posted in the form of debits and credits.

- **magnetic ink character recognition (MICR)**<a id="micr"></a>: Banking numbers (routing/transit number, checking account number, check number) that appear at the bottom of a check and enable high-speed processing.

- **magstripe** <a id = "magstripe"></a>: The magnetic strip on the back of a payment card that transmits card data during a transaction. In most cases, the magstripe is a “fallback” option in the event a chip malfunctions or cannot be read.

- **merchant**<a id="merchant"></a>: A business selling goods or services either in person (retailer) or remotely (website or mail order/telephone order) often accepting payment cards as a form of payment.

- **merchant category code (MCC)**<a id="mcc"></a>: A four-digit code that  defines a merchant’s business type with the card brands.

- **merchant identification number (MID)**<a id="mid"></a>: A number that numerically identifies each merchant to the merchant processor for accounting and billing purposes.

- **microdeposit**<a id="microdeposit"></a>: An account ownership verification tactic where a small amount is temporarily deposited into a user's bank account. The user must confirm the amount received. Once the user is verified, the microdeposits will be withdrawn from their account. See [instant account verification](#instant-account-verification).

- **mobile wallet**<a id="mobile-wallet"></a>: A type of [digital wallet](#digital-wallet), this is a software application usually used in conjunction with a mobile payment system to facilitate electronic payments using a smartphone for online transactions as well as purchases at physical stores. Mobile wallets need to be linked to a user’s bank or credit card account.

- **money market deposit account (MMDA)**<a id="mmda"></a>: Often considered a hybrid between a checking and savings account, it provides check writing and debit card privileges with limited access to funds. It has both a higher interest rate and minimum required balance than a savings account.

- **money service business (MSB)**<a id="money-service-business"></a>: A broad term that encompasses any organization that transmits or converts money. Examples include banks, check-cashing providers, and foreign currency exchanges. These organizations are regulated to prevent money laundering.

- **Money Transmitter License (MTL)**<a id="money-transmitter-license"></a>: A license for conducting money transfer services that is defined at the US state level. Many states require payments-related institutions to become a registered money transmitter by obtaining a license to operate in that particular state.

- **NACHA (National Automated Clearing House Association)**<a id="nacha"></a>: A nonprofit that manages the ACH network and is composed of various depository financial institutions. NACHA's role is to make rules and products for the ACH payment system and is not directly involved in transaction processing.

- **non-sufficient funds (NSF)**<a id="nsf"></a>: Occurs when a payment is attempted, but there aren’t enough funds in the account to cover it entirely. This commonly results in a fee and a canceled, or “bounced” payment. If the bank doesn’t cancel and covers the payment, it’s known as an [overdraft](#overdraft).

- **OCT (Original Credit Transaction)** <a id="oct"></a>: A card network transaction used to disburse or push funds in real-time to an eligible card account. Commonly referred to as push-to-card.

- **ODFI (Originating Depository Financial Institution)**<a id="odfi"></a>: An ODFI transmits ACH entries to an ACH operator on behalf of an originator, crediting or debiting their account as needed. Each ODFI warrants that the transaction is properly authorized and complies with the NACHA Operating Rules.

- **OFAC (Office of Foreign Assets Control)**<a id="ofac"></a>: The OFAC administers and enforces economic and trade sanctions based on U.S. foreign policy and national security goals against targeted foreign countries and regimes, terrorists, international narcotics traffickers, those engaged in activities related to the proliferation of weapons of mass destruction, and other threats to the national security, foreign policy, or economy of the United​ States.

- **offline debit transaction**<a id="offline-debit"></a>: Also known as a signature-debit transaction, this is a payment method utilizing a debit card without the use of a PIN. These transactions process in much the same way as a credit card transaction (funds are held but not debited immediately). An interchange fee is charged to the merchant and not the card-issuing bank. Offline debit transactions can occur in both a card present and card not present environment

- **online debit transaction**<a id="online-debit"></a>: Also known as a PIN-debit transaction, this is a payment method utilizing a debit card with the use of a PIN and uses a debit network such as STAR or Pulse. Funds are deducted from the cardholder’s bank account immediately upon transaction completion at the point of sale. Online debit transactions are only available in a card present environment.

- **on-us transaction**<a id="online-debit"></a>: A transaction where the sender and receiver banks are the same, resulting in fewer fees for the bank.

- **open-loop payment system**<a id="open-loop"></a>: Open-loop payment systems operate on a hub-and-spoke model requiring intermediaries (almost always banks or depository financial institutions) to join the payments system, then form business relationships with end parties.

- **origination**<a id="origination"></a>: This is the up-front, multi-step process by which a consumer or borrower applies for a new loan or credit card, and the lender or card issuer processes that application, covering all steps from application submission through approval/denial.

- **originator (ACH)**<a id="originator"></a>: The entity that starts an ACH payment transaction. The Originator is the consumer, business, or government organization that initiates the payment process and is authorized to do so.

- **overdraft**<a id="overdraft"></a>: Occurs when more money is spent than is available in a checking account. An overdraft fee will be charged, and the payment will be processed.

- **overlimit**<a id="overlimit"></a>: When a cardholder exceeds the predetermined credit limit on a payment card, that cardholder’s account is deemed over-limit. At that point, the card issuer may decline the transaction or process the transaction and then assess a penalty fee for surpassing the agreed-upon limit.

- **P2P (Peer-to-Peer)**<a id="p2p"></a>: Payments that involve the transfer of funds between two different parties’ accounts. These accounts may be at the same or different financial institutions. Examples of P2P include Venmo, Zelle, and Cash App.

- **partial authorization**<a id="partial-authorization"></a>: During a transaction, if the full amount of the transaction cannot be approved, the issuer can return a partial authorization. At the point of sale, the merchant then requests an additional method of payment to cover the outstanding balance of the transaction.

- **payment**<a id="payment"></a>: The transfer of value from one end party to another.

- **payment aggregator**<a id="payment-aggregator"></a>: A service provider that facilitates online payments by enabling merchants to accept transactions without the need to set up a merchant account with a bank.

- **payment facilitator (PayFac)**<a id="payfac"></a>: A master merchant account that services sub-merchants as an [underwriter](#underwriter), simplifying and speeding up the merchant enrollment process. This eliminates the need for sub-merchants to establish a direct relationship with an acquiring bank. Onboarded sub-merchants do not need to register a [merchant ID (MID)](#mid) and will instead fall under the PayFac's master MID.

- **Payment for Order Flow (PFOF)**<a id="pfof"></a>: A payment by an exchange to a brokerage firm for the right to execute a given trade.  While this is a controversial practice, the net result is often price improvement for the trader, relative to the price on the public exchange.

- **payment gateway**<a id="payment-gateway"></a>: An internet-based system used in an e-commerce transaction to transmit payment card information to a credit card processor for verification, completing the authorization process between the merchant and the consumer.

- **payment message structure (ISO 20022)**<a id="payment-message-iso20022"></a>: An ISO 20022 payment initiation message is composed of three parts: Group Header, Payment Information, and Credit Transfer Transaction Information.

- **payment method**<a id="payment-method"></a>: The form of payment a consumer uses to purchase goods or services from a seller (e.g., cash, credit card, debit card, money order, bank transfer).

- **payment rails**<a id =payment-rails></a>: The technological infrastructure for moving money from one party to another. Some examples of payment rails include ACH, RTP, and cards.

- **payment service provider (PSP)**<a id="psp"></a>: A payment service provider is a third party that provides merchants the ability to accept electronic payments, enabling connectivity to financial institutions and credit card acquirers.

- **PCI (Payment Card Industry) compliance**<a id="PCI compliance"></a>: Adherence to the security regulations set by the Payment Card Industry Data Security Standard (PCI DSS). PCI compliance is crucial for maintaining the ability to make card transactions and avoiding penalties.

- **personal identification number (PIN)**<a id="pin"></a>: A confidential individual number or code used by a cardholder to authenticate card ownership for ATM or POS-terminal transactions.

- **point-of-sale (POS)**<a id="point-of-sale"></a>: The specific time and place where a retail transaction is completed.

- **positive pay**<a id="positive-pay"></a>: A fraud-prevention system often used by enterprises to match checks presented for payment against a list of issued checks kept by the company.

- **prepaid card**<a id="prepaid-card"></a>: A payment card that is not linked to a bank account, where the cardholder can only spend up to the amount that has been pre-deposited onto the card. Prepaid cards are often reloadable.

- **primary account number (PAN)**<a id="pan"></a>: Numerical code, up to 16 digits, uniquely identifying a credit cardholder’s account, created when the account is opened. The first six numbers identify the card network, the next set of digits signifies the cardholder, and the remaining digits are used for security purposes. A primary account number starts with the [bank identification number (BIN)](#bin).

- **processor**<a id="processor"></a>: A third party that is designated by a merchant to handle credit card and debit card transactions between that merchant and its customers. They are often broken down into two types: front-end processors and back-end processors.

- **program manager**<a id="program manager"></a>: the entity responsible to an issuing bank for ensuring all risk and compliance requirements, network rules, and other standards are upheld for a particular card program.

- **procure-to-pay**<a id="procure-to-pay"></a>: The process of purchasing and paying for goods and services from vendors. This usually refers to an automated system that integrates procurement with accounts payable.

- **rapid dispute resolution (RDR)**<a id="rapid-dispute-resolution"></a>: RDR is a Visa pre-dispute solution that allows merchants to set rules and respond to pre-disputes with automatic refunds thereby preventing a chargeback at the pre-dispute stage.

- **RDFI (Receiving Depository Financial Institution)**<a id="odfi"></a>: An RDFI receives ACH entries from an ACH operator and credits or debits their customer's (receiver's) account as needed.

- **reason code**<a id="reason-code"></a>: A code used to provide additional information to the receiving clearing member regarding the nature of a chargeback, subsequent presentment, fee collection, funds disbursement, or request for a source document.

- **receiver**<a id="receiver"></a>: The intended recipient of an ACH transaction. The Receiver authorizes the Originator to initiate a transaction to either “push” or “pull” funds to/from the Receiver’s bank account, depending on whether an ACH credit or debit transaction was generated by the Originator.

- **recurring billing**<a id="recurring-billing"></a>: A transaction charged (with prior permission) on a periodic basis for recurring goods and services, (e.g., health-club memberships, book-of-the-month clubs).

- **refund transaction**<a id = "refund transaction"></a>: A transaction that gives money back to the cardholder after the initial sale has completed settlement. Unlike a void, a refund results in money being moved from the merchant to the cardholder and Interchange fees may be applied. A refund can only be initiated if an offsetting sale exists.

- **Regulation E**<a id="regulation-e"></a>: Refers to 12 CFR Part 1005, a regulation issued by the Consumer Financial Protection Bureau, pursuant to the Electronic Funds Transfer Act, that establishes the basic rights, liabilities, and responsibilities of consumers who use [electronic funds transfer (EFT)](#eft) services.

- **remote deposit transfer**<a id="remote-deposit"></a>: The process of customers making deposits remotely by scanning checks, often using a mobile device.

- **retrieval request**<a id="retrieval-request"></a>: Sent from an issuer to an acquirer, this is a request for detailed information regarding a completed transaction. This often occurs when there is potential for a [chargeback](#chargeback).

- **return code**<a id="return-code"></a>: A notification of a payment return or correction for a business or user.

- **risk management**<a id="risk-management"></a>: The process of identifying potential sources of risk and attempting to mitigate them. In payments, major types of risk include credit risk, fraud, and data security.

- **routing number**<a id="routing-number"></a>: Series of numbers assigned to checking accounts, savings accounts, or other accounts that identify the financial institution associated with the specific account.

- **real-time gross settlement (RTGS)**<a id="rtgs"></a>: The continuous process of settling payments on an individual basis in real time, rather than submitting files at the end of the day or at predetermined intervals throughout the day.

- **RTP (Real-Time Payments)**<a id="rtp"></a>: Released in 2017, the RTP network from The Clearing House is a real-time payments platform that all federally insured U.S. depository institutions are eligible to use for payments innovation. It will soon compete with [FedNow](#fednow).

- **RTP Credit Transfer**<a id="rtp-credit-transfer"></a>: The basic multi-purpose payment message used for multiple use cases, including remittance information for [RTP transactions](#rtp-transaction).

- **RTP Event**<a id="rtp-event"></a>: An exchange of related [transactions](#rtp-transaction) between two financial institutions through the RTP System that constitutes a complete conversation. This could include one or more transactions. For example, a (1) Request for Payment Transaction, followed by a (2) Credit Transfer Transaction, followed by a (3) Payment Acknowledgement Transaction.

- **RTP Leg**<a id="rtp-leg"></a>: A transmission from a financial institution (FI) to the RTP System or the RTP System to an FI. It should be noted that either FI may initiate an RTP Instruction.

- **RTP Message**<a id="rtp-message"></a>: Transmission of an Instruction or Response from one financial institution to another through the RTP System.

- **RTP Request for Information**<a id="rtp-rfi"></a>: A payment-related message that a Receiving Participant submits to the RTP System for delivery to a Sending Participant, requesting additional information from a Customer in connection with an RTP Payment or Request for Payment.

- **RTP Request for Payment**<a id="rtp-rfp"></a>: A payment-related message that a Message Sender submits to the RTP System to deliver to a Message Receiver to request an RTP Payment from a Customer of a Message Receiver.

- **RTP Request for Return of Funds**<a id="rtp-rfr"></a>: A payment-related message that a Sending Participant submits to the RTP System to request return of funds related to an RTP Payment.

- **RTP Response to Request for Information**<a id="rtp-rrfi"></a>: A payment-related Request Response Message sent to answer with information requested by a [Request for Information Message](#rtp-rfi).

- **RTP Response to Request for Payment**<a id="rtp-rrfp"></a>: A payment-related Response Request Message sent to answer with information requested by a [Request for Payment Message](#rtp-rfp).

- **RTP Response to Request for Return of Funds**<a id="rtp-rrfr"></a>: A payment-related Request Message Response that a Receiving Participant submits to the RTP System with information in response to a [Request for Return of Funds Message](#rtp-rfr).

- **RTP Third Party Service Provider**<a id="rtp-tpsp"></a>: A commercial data processing service organization, data transmission facility, or any other Participant that acts on behalf of another Participant to transmit and receive Payment Messages, Payment Message Responses, and Non-Payment Messages through the RTP System.

- **RTP Transaction**<a id="rtp-transaction"></a>: A full round trip of Instruction and Response messages. All Payment Transactions have five [legs](#rtp-leg) including the payee's financial institution confirmation leg. Payment-related Transactions have four legs and RTP Control Messages have two legs.

- **Same-day ACH**<a id="same-day-ach"></a>: Delivery of available funds within the same business day, not instead of the typical two to four day window.

- **savings account**<a id="savings-account"></a>: An interest-bearing account that offers limited access to funds to encourage savings goals. A minimum balance may be required.

- **settlement**<a id="settlement"></a>: The actual movement of funds from one financial institution to another that completes a transaction.

- **skimming**<a id="skimming"></a>: A type of fraud, where a device called a skimmer is placed over a legitimate card reader and captures info when a user unknowingly swipes their card through.

- **sponsor bank**<a id="sponsor-bank"></a>: A licensed financial institution that handles funds transmission and may provide additional banking services for a company's customers within a [BaaS](#baas) model, which lets the company avoid having to obtain a license themselves.

- **stablecoin**<a id="stablecoin"></a>: A cryptocurrency designed to have a stable value by being pegged to a fiat currency or other assets like gold.

- **standard entry class (SEC) code**<a id="sec"></a>: A three character code to identify the format and application of an ACH transaction.

- **standard industrial classification (SIC) code**<a id="sic"></a>: A four-digit code assigned by the United States government that classifies industries and is used to identify the nature of a business.

- **straight-through processing (STP)**<a id="stp"></a>: Payment processing that is completely free of human intervention, resulting in faster completion and fewer errors.

- **terminal identification number (TID)**<a id="tid"></a>: A unique numerical identifier that denotes the specific point-of-sale device or computer where a payment card transaction is initiated.

- **The Clearing House (TCH)**<a id="tch"></a>: A banking association and payments company owned by large commercial banks that provides the only private-sector ACH ([EPN](#epn)) and wire ([CHIPS](#chips)) operators in the United States.

- **thin file**<a id="thin-file"></a>: The credit report of someone with little or no credit history, which may make it difficult to access credit.

- **TIN validation**<a id="tin-validation"></a>: An IRS program that allows payers to match the tax identification number (TIN) of a business or individual to the IRS database when filing [1099](#1099) forms. This helps avoid penalties from filing invalid 1099s.

- **trace ID**<a id="trace-id"></a>: A unique reference number assigned to each ACH entry, also known as a "trace number", which can be used to “trace” the location of the transfer.

- **ultimate creditor**<a id="ultimate-creditor"></a>: The party that is the ultimate beneficiary of a payment. For example, the payment is credited to an account of a financing company, but the ultimate beneficiary is the customer of the financing company.

- **ultimate debtor**<a id="ultimate-debtor"></a>: The party that owes an amount of money to the ultimate creditor, such as the buyer of services or goods. This term is used when the receiver of an invoice is different from the payer.

- **unauthorized transaction**<a id="unauthorized-transaction"></a>: The use of a credit or debit card, or other method, to make a payment not authorized by the account holder, often the result of fraud or cybercrime. Note that this does not refer to an issuer declining authorization for payment on a transaction.

- **underbanked**<a id="underbanked"></a>: Having a bank account, but lacking access to additional financial services such as credit cards or loans.

- **under review**<a id="under-review"></a>: The payment processor practice of reviewing a potentially fraudulent or high-risk transaction prior to submission for processing, usually resulting in a minor delay.

- **underwriter**<a id="underwriter"></a>: A party that evaluates and assumes another party’s risk for a fee.

- **value-added reseller (VAR)**<a id="var"></a>: An entity that resells a product after adding some additional value, often in the form of warranties, customer support, consultations, or integration with other products.

- **void transaction**<a id="void-transaction"></a>: An authorization that is canceled prior to settlement. A void stops any actual money movement between a merchant and a cardholder and is not billed interchange fees.


## Sales

- **churn rate**<a id="churn-rate"></a>: The percentage of customers who stop using a service during a specific time period. It's often used as a key metric in subscription-based businesses.

- **customer relationship management (CRM)**<a id="crm"></a>: One of many different approaches that allows a company to manage and analyze its own interactions with its past, current, and potential customers.

- **horizontal market**<a id="horizontal"></a>: A non-specialized market that doesn’t focus on a single niche and covers a wide range of industries (e.g., office supplies).

- **lead scoring**<a id="lead-scoring"></a>: A method used in sales to assign a score to prospects based on their likelihood to become a customer, often determined by behavior, demographics, or engagement.

- **letter of intent (LOI)**<a id="loi"></a>: A document declaring the preliminary commitment of one party to do business with another. The letter outlines the chief terms of a prospective deal.

- **master service agreement (MSA)**<a id="msa"></a>: A contract reached between parties, in which the parties agree to most of the terms that will govern future transactions or future agreements. A master agreement permits the parties to quickly enact future transactions or agreements, negotiating only the points specific to the new transactions and relying on the provisions in the master agreement for common terms.

- **non-disclosure agreement (NDA)**<a id="nda"></a>: A non-disclosure agreement is a legally binding contract that establishes a confidential relationship. The party or parties signing the agreement agree that sensitive information they may obtain will not be made available to any others.

- **vertical market**<a id="vertical"></a>: a market that focuses on a specific industry, sector, or audience (e.g., organic grocery products).


## Software and Technology

- **API (Application Programming Interface)**<a id="api"></a>: A computing interface which defines interactions between multiple software intermediaries. It defines the kinds of calls or requests that can be made, how to make them, the data formats that should be used, the conventions to follow, etc.

- **BaaS (Banking as a Service)**<a id="baas"></a>: A modular approach to supplying complete banking processes that allows brands to easily embed financial services into their products without having to worry about building banking infrastructure or obtaining a license. BaaS utilizes [APIs](#api) and [webhooks](#webhooks) to make integration seamless and cost-effective.

- **batch processing**<a id="batch-processing"></a>: A type of data processing and data communications transmission in which related transactions are grouped together and transmitted en masse for processing, usually by the same computer and under the same application.

- **decentralized finance (DeFi)**<a id="defi"></a>: An umbrella term for blockchain-based financial services that remove intermediaries like banks, allowing users to lend, borrow, trade, and save cryptocurrencies.

- **encryption**<a id="encryption"></a>: The technique of scrambling sensitive data automatically in a terminal or computer before transmission for security/anti-fraud purposes using an algorithm and key. This is similar to [tokenization](#tokenization).

- **JSON (JavaScript Object Notation)**<a id="json"></a>: A syntax for storing and exchanging data compatible with most programming languages.

- **maintainer**<a id="maintainer"></a>: An open source software developer responsible for a project's overall health and roadmap. They decide whether to accept new contributions by weighing long-term costs and determining net benefit. Maintainers will often review code submissions in the form of pull requests (PRs) and manage issue tracking among other vital tasks. A maintainer is not always a project's original author.

- **NFC (Near Field Communication)**<a id="nfc"></a>: Payment card technology that uses short-range wireless connectivity to transmit payment data securely. NFC can be used with payment cards as “contactless” payments or with mobile wallets such as GooglePay or ApplePay.

- **OSS (Open Source Software)**<a id="oss"></a>: Collaborative software where source code is released publicly, granting users the rights to use, view, modify, and distribute the software to anyone and for any purpose.

- **production environment**<a id="production-environment"></a>: This is for the final stage of development, and where real users directly interact and testing is complete.

- **SaaS (Software as a Service)**<a id="saas"></a>: A software licensing and delivery model in which software is licensed on a subscription basis and centrally hosted. It is sometimes referred to as "on-demand software".

- **sandbox environment**<a id="sandbox environment"></a>: A testing environment for trial, experimentation, or demonstration purposes.

- **smart contract*<a id="smart-contract"></a>: A self-executing contract with the terms of the agreement between buyer and seller directly written into lines of code. Smart contracts are typically used on blockchain platforms.

- **staging environment**<a id="staging-environment"></a>: This is used for testing or demos and very closely resembles a [production environment](#production-environment).

- **tokenization**<a id="tokenization"></a>: Data-security technology that substitutes non-sensitive random numerical sequences for sensitive data so it can be passed over the internet without exposing the raw data. This is similar to [encryption](#encryption).

- **webhooks**<a id="webhooks"></a>: Automated messages sent from an app when an event occurs. The vendor will send an HTTP POST request containing desired data to a URL provided by the customer. The customer should refer to vendor documentation for payload format information.

- **X9**<a id="x9"></a>: The standard format for image cash letters. It addresses the file sequences, record types, field formats, data and image compression, and data representation. See [Check 21](#check-21).

- **XML (Extensible Markup Language)**<a id="xml"></a>: Similar in appearance to HTML, this dynamic language lets you define your own tags within a standardized syntax rather than use predefined ones. It's also used for transporting data, not displaying it.


## ACH Standard Entry Class Codes

- **ACK**<a id="ack"></a>: for acknowledging receipt of a [CCD](#ccd) entry

- **ADV (Automated Accounting Advice)**<a id="adv"></a>: An optional service provided by ACH operators that identifies automated accounting advice of ACH accounting information in machine-readable format to facilitate the automation of accounting information for participating depository financial institutions.

- **ARC (Accounts Receivable Entry)**<a id="arc"></a>: occurs when a consumer check is received at a bank lockbox that’s serving a biller and converted into ACH

- **ATX**<a id="atx"></a>: for acknowledging receipt of a [CTX](#ctx) entry

- **BOC (Back Office Conversion)**<a id="boc"></a>: occurs when a consumer check is received at a point of sale and converted into ACH during back office processing

- **CCD (Corporate Credit or Debit)**<a id="ccd"></a>: for [B2B](#b2b) transactions, often between a supplier and their corporate customers

- **CIE (Customer-Initiated Entry)**<a id="cie"></a>: used for single bill payments

- **COR (Notification of Change)**<a id="cor"></a>: a non-dollar entry transmitted from RDFI to ODFI in response to outdated or erroneous information in an initial entry

- **CTX (Corporate Trade Exchange)**<a id="ctx"></a>: a [B2B](#b2b) transaction similar to [CCD](#ccd) that includes addenda records

- **DNE (Death Notification)**<a id="dne"></a>: a notice made by the federal government to notify an RDFI of the death of a receiver

- **ENR (Automated Enrollment)**<a id="enr"></a>: a non-dollar entry sent by an RDFI to enroll a receiver in benefit payments from a federal government agency

- **IAT (International ACH Transaction)**<a id="iat"></a>: used for international transactions

- **MTE (Machine Transfer Entry)**<a id="mte"></a>: for transactions initiated at ATMs

- **POP (Point-of-Purchase)**<a id="pop"></a>: occurs when a consumer check is received at a point of sale and converted into ACH immediately

- **POS (Point-of-Sale)**<a id="pos"></a>: occurs when a consumer initiates a payment, typically via card, at a point of sale

- **PPD (Prearranged Payment and Deposit)**<a id="ppd"></a>: for preauthorized transactions where credits are business to consumer (e.g., payroll) and debits are consumer to business (e.g., bill payments)

- **RCK (Re-presented Check)**<a id="rck"></a>: used by originators to re-present a check that was presented and returned due to insufficient or uncollected funds

- **SHR (Shared Network)**<a id="shr"></a>: See [POS](#POS).

- **TEL (Telephone-Initiated)**<a id="tel"></a>: for single or recurring debit transactions authorized over phone

- **TRC (Truncated Check Entry)**<a id="trc"></a>: used for single truncated checks

- **TRX (Truncated Check Entries Exchange)**<a id="trx"></a>: a batch of TRC entries represented as addenda records

- **WEB (Web-Initiated)**<a id="web"></a>: for single or recurring credit or debit transactions authorized over the Internet

- **XCK (Destroyed Check Entries)**<a id="xck"></a>: used by an ODFI when checks are lost, destroyed, or unreadable


## Moov's open source projects
As part of Moov's initiative to offer open source fintech infrastructure, we have a large collection of active projects you may find useful:

- [**Moov ACH**](https://github.com/moov-io/ach): provides ACH file generation and parsing, supporting all Standard Entry Codes for the primary method of money movement throughout the United States.

- [**Moov Fed**](https://github.com/moov-io/fed): implements utility services for searching the United States Federal Reserve System such as ABA routing numbers, financial institution name lookup, and FedACH and Fedwire routing information.

- [**Moov Fincen**](https://github.com/moov-io/fincen):
implements a reader, writer, and validator for Fincen BSA forms in an HTTP server and Go library. It is capable of generating, validating, and batching submissions.

- [**Moov Image Cash Letter**](https://github.com/moov-io/imagecashletter): implements Image Cash Letter (ICL) files used for Check21, X.9 or check truncation files for exchange and remote deposit in the U.S.

- [**Moov IRS**](https://github.com/moov-io/irs): implements a reader and writer for IRS FIRE (Filing Information Returns Electronically).

- [**Moov ISO 8583**](https://github.com/moov-io/iso8583): offers a message reader and writer for ISO 8583, a widely used, international standard for card-originated financial transactions that defines both message format and communication flow.

- [**Moov ISO 20022**](https://github.com/moov-io/iso20022): offers a message reader and writer for ISO 20022, a modern standard for electronic data interchange between financial institutions.

- [**Moov Metro 2**](https://github.com/moov-io/metro2): provides a way to easily read, create, and validate Metro 2 format, which is used for consumer credit history reporting by the United States credit bureaus.

- [**Moov Watchman**](https://github.com/moov-io/watchman): offers search functions over numerous trade sanction lists from the United States and European Union.

- [**Moov Wire**](https://github.com/moov-io/wire): implements an interface to write files for the Fedwire Funds Service, a real-time gross settlement funds transfer system operated by the United States Federal Reserve Banks.

