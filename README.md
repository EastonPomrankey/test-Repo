# User Story: Ad Panel Sidebar

## ID: 01

## Title: As a client, I want the website to display ads in a sidebar so that it generates revenue without disrupting the user experience.

## Assumptions / Preconditions

- The recipe page has been implemented.
- Ads have been obtained by management/sponsors.
- The ad content is provided via an ad management system or database.

## Description

The ad panel should be visible but unobtrusive so users can browse recipes without feeling overwhelmed. Ads should be small enough to avoid disrupting the main content but
large enough to be noticed and clicked, supporting website revenue goals. The panel should automatically rotate ads or display relevant ads based on recipe content or user
behavior to improve click-through rates and user interests. Here are some key requirements after the discussion with the client:

1. Ads are always visible but do not block or cover the recipe content.
2. Ads do not auto-play sounds or videos, and avoid pop-ups or overlay.
3. The panel should display multiple ads in a scrolling or rotating format to give visibility to different ads.
4. Users should still be able to interact fully with recipes without the ad panel affecting usability.
5. The design should balance business needs with user experience.
6. The ad panel should be responsive on desktops, tablets or mobile devices.

## Acceptance Criteria (Given / When / Then Format)

### Sidebar visibility

**Given** the user is on a recipe list page or recipe detail page,  
**When** the page loads,  
**Then** the sidebar ad panel should be visible on the right side of the screen.

### Ads display properly

**Given** an ad is loaded into the ad panel,  
**When** the user views the page,  
**Then** the ad should be clearly displayed, fully visible, and not overlap recipe content.

### Ads are clickable

**Given** an ad is displayed in the panel,  
**When** the user clicks the ad,  
**Then** the user should be taken to the advertiser’s link without affecting the recipe page layout.

### Multiple ads dynamically rotate

**Given** multiple ads are available in the system,  
**When** the user spends time on the page,  
**Then** the ad panel should rotate or update to show additional ads automatically.

### No intrusive behavior

**Given** the user is browsing recipes,  
**When** the ad panel is active,  
**Then** ads should not pop up, auto-play audio/video, or obstruct the user’s interaction.

### Tailored ads after prolonged use

**Given** the user has used the website for an extended period,  
**When** the system has collected enough behavior data,  
**Then** the user should begin seeing more tailored or relevant ads.

### Recipe interaction not blocked

**Given** the ad panel is visible on the page,  
**When** the user scrolls, clicks, comments, or interacts with a recipe,  
**Then** the ad panel should not interrupt, cover, or prevent interaction with recipe features.

## Tasks

1. Design the sidebar layout for the ad panel, ensuring it doesn’t cover recipe cards or main content.
2. Implement the ad panel in the front-end using HTML/CSS, ensuring proper sizing and spacing.
3. Connect the ad panel to the ad database or ad management system to fetch ad content dynamically.
4. Ensure ads are clickable and track click-through rates for analytics.
5. Implement rotation or scrolling logic for multiple ads to display over time.
6. Write unit tests to verify that the ad panel renders correctly.
7. Perform integration testing with recipe pages to ensure smooth interaction between recipe content and ads.
8. Test user experience to ensure ads are visible but not intrusive. Do this by confirming they don’t interfere with recipe interaction through public comment.
9. Implement a responsive design for mobile devices.

## Effort Points:

## Dependencies:

- Recipe cards and recipe pages must be implemented first.
- The ad database or ad content must be available for integration.

## Owner:

## Git Feature Branch:

Ad panel

## Modeling Documents:
