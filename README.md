# Amadeus Solutions (amadeus-solutions)
Amadeus is a leading technology partner for the global travel industry, providing technology solutions for airlines, airports, hotels, travel sellers, and corporate travel. The Amadeus platform includes a global distribution system (GDS), passenger service systems, airport operations, hospitality management, and a suite of APIs enabling developers to search, price, book, and manage travel across air, hotel, and ground transportation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amadeus-solutions/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Airlines, Booking, Flights, GDS, Hotels, Travel, Travel Technology

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Flight Offers Search API
The Amadeus Flight Offers Search API enables searching and comparing flight offers from over 400 airlines. Search one-way, round-trip, or multi-city itineraries with cabin class, baggage, and pricing filters. Returns comprehensive fare details including branded fares, ancillaries, and pricing breakdowns.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)

#### Tags:

 - Airlines, Flights, Search, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search)
- [APIReference](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search/api-reference)
- [OpenAPI](openapi/amadeus-solutions-flight-offers-search-openapi.yaml)

### Flight Offers Price API
The Amadeus Flight Offers Price API confirms the availability and price of a flight offer before booking. Validates current pricing, seat availability, and fare conditions for offers returned by Flight Offers Search, ensuring accurate pricing at time of reservation.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)

#### Tags:

 - Airlines, Flights, Pricing, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-price)
- [OpenAPI](openapi/amadeus-solutions-flight-offers-price-openapi.yaml)

### Branded Fares Upsell API
The Amadeus Branded Fares Upsell API provides upgrade options for travelers, enabling upsell from basic economy to premium economy, business, or first class branded fares. Returns available upgrade options with fare families, services included, and price differences.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)

#### Tags:

 - Airlines, Ancillaries, Flights, Upsell

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/branded-fares-upsell)
- [OpenAPI](openapi/amadeus-solutions-branded-fares-upsell-openapi.yaml)

### Seat Map Display API
The Amadeus Seat Map Display API provides cabin layout and seat availability information for a flight. Returns detailed seat maps with seat characteristics, availability status, and pricing for seat selection during the booking process.

**Human URL:** [https://developers.amadeus.com/self-service/category/flights/api-doc/seat-map-display](https://developers.amadeus.com/self-service/category/flights/api-doc/seat-map-display)

#### Tags:

 - Airlines, Ancillaries, Flights, Seats

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/flights/api-doc/seat-map-display)
- [OpenAPI](openapi/amadeus-solutions-seat-map-display-openapi.yaml)

## Common Properties

- [Portal](https://developers.amadeus.com/)
- [GettingStarted](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [SignUp](https://developers.amadeus.com/register)
- [Pricing](https://developers.amadeus.com/pricing)
- [Blog](https://developers.amadeus.com/blog)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Support](https://developers.amadeus.com/support)
- [TermsOfService](https://developers.amadeus.com/legal/terms-and-conditions)
- [PrivacyPolicy](https://developers.amadeus.com/legal/privacy-policy)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [Python SDK](https://github.com/amadeus4dev/amadeus-python)
- [Node.js SDK](https://github.com/amadeus4dev/amadeus-node)
- [Java SDK](https://github.com/amadeus4dev/amadeus-java)
- [StatusPage](https://developers.amadeus.com/status)

## Solutions

| Name | Description |
|------|-------------|
| Amadeus Nevio (Airline Retailing) | Next-generation airline retailing platform enabling offer and order management for airlines pursuing NDC-based retailing strategies. |
| Amadeus Altéa (Passenger Service System) | Core passenger service system for full-service carriers providing reservations, inventory management, and departure control. |
| Amadeus Selling Platform Connect | Distribution platform for travel agencies providing GDS access, NDC content, and LCC integrations through a unified API. |
| Amadeus Cytric (Corporate Travel) | Corporate travel and expense management platform integrated with Microsoft Teams and major enterprise collaboration tools. |
| Amadeus Airport IT | Airport operations technology including baggage, passenger experience, ground handling, and border control solutions. |

## Features

| Name | Description |
|------|-------------|
| Global Flight Inventory | Access flight schedules and availability from over 400 airlines through a single integration with the Amadeus GDS. |
| NDC Content Support | Connect to airline NDC offers alongside traditional GDS content for a comprehensive view of available fares and ancillaries. |
| Branded Fares and Fare Families | Display branded fare options with included services, restrictions, and price differences to enable informed purchase decisions. |
| Ancillary Services | Access seat selection, baggage, meals, and other ancillary services through integrated APIs alongside fare shopping. |
| Real-Time Pricing | Confirm current pricing and availability before booking with the Flight Offers Price API to prevent pricing discrepancies. |

## Use Cases

| Name | Description |
|------|-------------|
| Flight Search and Booking Engine | Build complete flight shopping experiences searching, pricing, and booking flights across hundreds of airlines through a unified API. |
| Airline Retailing Platform | Power airline direct channels with offer creation, branded fares, seat maps, and ancillary upsell capabilities. |
| Corporate Travel Management | Enable policy-compliant flight shopping for corporate travelers with fare filtering, approval workflows, and reporting. |
| Travel Metasearch | Aggregate flight offers for price comparison across airlines with detailed fare family and service information. |
| AI Travel Assistant | Enable conversational travel assistants to search and compare flights using natural language queries. |

## Integrations

| Name | Description |
|------|-------------|
| Amadeus Flight Create Orders | Convert searched and priced flight offers into confirmed bookings using the Flight Create Orders API. |
| Amadeus Hotel Search | Combine flight search with hotel search to build complete trip planning experiences for travelers. |
| Amadeus Points of Interest | Enhance destination content alongside flight search with attractions, experiences, and activities data. |
| Amadeus Transfer Search | Add ground transportation options to flight itineraries through the Transfer Search API. |
| Outpayce (Payments) | Integrate travel payments processing through Amadeus Outpayce for airline and OTA payment acceptance. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amadeus Flight Offers Search OpenAPI](openapi/amadeus-solutions-flight-offers-search-openapi.yaml)
- [Amadeus Flight Offers Price OpenAPI](openapi/amadeus-solutions-flight-offers-price-openapi.yaml)
- [Amadeus Branded Fares Upsell OpenAPI](openapi/amadeus-solutions-branded-fares-upsell-openapi.yaml)
- [Amadeus Seat Map Display OpenAPI](openapi/amadeus-solutions-seat-map-display-openapi.yaml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Flight Offers Search API](capabilities/shared/flight-offers-search.yaml) — 2 operations for flight search
- [Flight Offers Price API](capabilities/shared/flight-offers-price.yaml) — 1 operation for price confirmation

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Flight Shopping](capabilities/flight-shopping.yaml) | Flight Offers Search API, Flight Offers Price API | 3 | OTA Developer, Travel Chatbot Developer |

## Vocabulary

- [Amadeus Solutions Vocabulary](vocabulary/amadeus-solutions-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amadeus Solutions Spectral Rules](rules/amadeus-solutions-spectral-rules.yml) — 15 rules across 6 categories enforcing Amadeus Solutions API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
