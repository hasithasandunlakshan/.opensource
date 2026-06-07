<div align="center">

<img src="https://github.com/hasithasandunlakshan.png" width="150" height="150" alt="hasithasandun" style="border-radius: 50%; border: 3px solid #0969da;"/>

# hasithasandun

**Open Source Contributor** • Sri Lanka

Full Stack Developer @ Upwork | Engineering Undergraduate at University of Moratuwa

[GitHub](https://github.com/hasithasandunlakshan) • [Web Portfolio](https://hasithasandunlakshan.github.io/.opensource/)

---

### Portfolio Summary

</div>

<table align="center">
  <tr>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">24</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Contributions</p>
    </td>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">3</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Projects</p>
    </td>
    <td align="center" width="200" style="padding: 20px;">
      <h2 style="margin: 0; font-size: 2.5em;">1</h2>
      <p style="margin: 5px 0 0 0; font-weight: 600;">Languages</p>
    </td>
  </tr>
</table>

<br/>

---

## Contributions by Project


### <img src="https://github.com/supabase.png" width="28" height="28" align="absmiddle" alt="supabase"> [supabase/supabase](https://github.com/supabase/supabase)

The Postgres development platform. Supabase gives you a dedicated Postgres database to build your web, mobile, and AI applications.

**1 contribution** • TypeScript • **★ 103,430**

---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [migrate auth policy editor modal to dialog](https://github.com/supabase/supabase/pull/46374) <sub>[#46374](https://github.com/supabase/supabase/pull/46374)</sub>

<sub><strong>Merged</strong> on May 26, 2026</sub>

- **Changes:** <code>+81</code> <code>-84</code> across 4 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/1122076?u=f0c921a9936a7af17c272ca8857044c079ccd225&v=4" width="24" height="24" align="absmiddle" alt="djhi" title="djhi">


<details>
<summary>View PR description</summary>

## I have read the [CONTRIBUTING.md](https://github.com/supabase/supabase/blob/master/CONTRIBUTING.md) file.

YES

## What kind of change does this PR introduce?

Refactor

## What is the current behavior?

The Auth policy editor flow still uses the deprecated `Modal` component and `Modal.Content` / `Modal.Separator` helpers.

## What is the new behavior?

The Auth policy editor flow now uses `Dialog` primitives instead:

- `Dialog`
- `DialogContent`
- `DialogHeader`
- `DialogTitle`
- `DialogSection`
- `DialogSectionSeparator`

Behavior is intended to remain unchanged.

## Additional context

- Fixes #46375 



## Summary by CodeRabbit

* **Refactor**
  * Updated the policy editor and review flows to a unified dialog layout for a cleaner, more consistent UI.
  * Sections and footer controls were reorganized for clearer grouping and improved button placement.
  * Existing behaviors (viewing templates, review/save flow, and close confirmation) are preserved.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/supabase/supabase/pull/46374?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>



---


### <img src="https://github.com/supabase-community.png" width="28" height="28" align="absmiddle" alt="supabase-community"> [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp)

Connect Supabase to your AI assistants

**1 contribution** • TypeScript • **★ 2,713**

---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [resolve edge function test typo and invalid branch array access](https://github.com/supabase-community/supabase-mcp/pull/279) <sub>[#279](https://github.com/supabase-community/supabase-mcp/pull/279)</sub>

<sub><strong>Merged</strong> on May 15, 2026</sub>

- **Changes:** <code>+16</code> <code>-5</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/4133076?u=f3f783e0364abe955dbde6af80445ea27d948fdd&v=4" width="24" height="24" align="absmiddle" alt="gregnr" title="gregnr">


<details>
<summary>View PR description</summary>

## What kind of change does this PR introduce?

Bug fix

## What is the current behavior?

1. The `delete branch` test case in `server.test.ts` fails in standard JavaScript environments due to an invalid negative array index `branches[-1]`.
2. There is a typo in one of the Edge Function test descriptions: `eploy edge function validates slug format`.

## What is the new behavior?

1. Replaces `branches[-1]` with the modern JavaScript `.at(-1)` method to safely access the last element of the array.
2. Corrected the typo from `eploy` to `deploy`.

## Additional context

These issues were identified while implementing new database tools. Resolving them ensures a stable test suite for all contributors.

</details>



---


### <img src="https://github.com/asyncapi.png" width="28" height="28" align="absmiddle" alt="asyncapi"> [asyncapi/website](https://github.com/asyncapi/website)

AsyncAPI specification website

**22 contributions** • TypeScript • **★ 707**

---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [implement FilterDropdown component and replace Select in Filtercomponent](https://github.com/asyncapi/website/pull/5531) <sub>[#5531](https://github.com/asyncapi/website/pull/5531)</sub>

<sub><strong>Merged</strong> on Jun 7, 2026</sub>

- **Changes:** <code>+129</code> <code>-17</code> across 3 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- The current dropdown filter on the blog page was using the full device height. Because it relied on the native HTML `<select>` element, it was difficult to style and control.
- Implemented a simple custom dropdown component to replace it, which correctly manages the height and fully supports both dark and light themes.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| **Light** | <img width="1512" height="954" alt="Light Theme Before" src="https://github.com/user-attachments/assets/851696f3-e20f-47c5-af0e-777b492ce083" /> | <img width="822" height="660" alt="Light Theme After" src="https://github.com/user-attachments/assets/efd2c7b6-301c-4ce7-bb1a-ae685b331cfb" /> |
| **Dark** | <img width="1512" height="952" alt="Dark Theme Before" src="https://github.com/user-attachments/assets/2fc95806-3e57-4fa6-893f-c2aa2afd17be" /> | <img width="809" height="722" alt="Dark Theme After" src="https://github.com/user-attachments/assets/358818d1-b659-4529-b8cb-0636d56a7ef4" /> |

**Reproduce**

1. Navigate to the blog page at https://deploy-preview-5531--asyncapi-website.netlify.app/blog.
2. Click on the category filter to open the dropdown.
3. Verify that the custom dropdown renders correctly and does not stretch to the full device height.
4. Toggle between the light and dark themes to check the styling.

**Related issue(s)**


## Summary by CodeRabbit

* **New Features**
  * Replaced legacy select controls with a single‑select filter dropdown for type/author/tag — adds a dedicated dropdown component, outside‑click and Escape‑to‑close behavior, rotating caret visual state, and ARIA accessibility improvements.
* **Tests**
  * End-to-end tests updated to drive and assert the new dropdown controls, including robust option matching and selecting the first available option.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [update broken allcontributors and TSC_MEMBERSHIP links](https://github.com/asyncapi/website/pull/5545) <sub>[#5545](https://github.com/asyncapi/website/pull/5545)</sub>

<sub><strong>Merged</strong> on Jun 7, 2026</sub>

- **Changes:** <code>+8</code> <code>-7</code> across 4 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

This PR fixes several broken external links found across the website's documentation and configuration files. The `allcontributors.org` site restructured its URL paths from `/docs/en/` to `/en/reference/`, and the `TSC_MEMBERSHIP.md` file was moved from the root of the `asyncapi/community` repo to a subdirectory, making the old hardcoded path return a 404.

**Changes made:**

- Updated the `TSC_MEMBERSHIP` constant in `FooterList.ts` to point to the correct subdirectory path
- Updated All Contributors specification links across documentation files
- Updated All Contributors emoji-key links across documentation files
- Updated the All Contributors bot link from the bare domain to the proper `/en/bot/` path

**Link changes (old → new):**

| File | Old URL | New URL |
|------|----------|----------|
| `components/footer/FooterList.ts` | [https://github.com/asyncapi/community/blob/master/TSC_MEMBERSHIP.md](https://github.com/asyncapi/community/blob/master/TSC_MEMBERSHIP.md) | [https://github.com/asyncapi/community/blob/master/docs/020-governance-and-policies/TSC_MEMBERSHIP.md](https://github.com/asyncapi/community/blob/master/docs/020-governance-and-policies/TSC_MEMBERSHIP.md) |
| `CONTRIBUTING.md` | [https://allcontributors.org/docs/en/specification](https://allcontributors.org/docs/en/specification) | [https://allcontributors.org/en/reference/specification/](https://allcontributors.org/en/reference/specification/) |
| `markdown/about/index.md` | [https://allcontributors.org/docs/en/specification](https://allcontributors.org/docs/en/specification) | [https://allcontributors.org/en/reference/specification/](https://allcontributors.org/en/reference/specification/) |
| `markdown/about/index.md` | [https://allcontributors.org](https://allcontributors.org) | [https://allcontributors.org/en/bot/](https://allcontributors.org/en/bot/) |
| `markdown/docs/.../recognize-contributors.md` | [https://allcontributors.org/docs/en/specification](https://allcontributors.org/docs/en/specification) | [https://allcontributors.org/en/reference/specification/](https://allcontributors.org/en/reference/specification/) |
| `markdown/docs/.../recognize-contributors.md` | [https://allcontributors.org/docs/en/emoji-key](https://allcontributors.org/docs/en/emoji-key) | [https://allcontributors.org/en/reference/emoji-key/](https://allcontributors.org/en/reference/emoji-key/) |

**Related issue(s)**


## Summary by CodeRabbit

* **Documentation**
  * Standardized and updated documentation links and reference paths across the site.
  * Refreshed contributor recognition links (All Contributors spec and bot) and updated governance/membership document links to their current locations.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [broken-url-in-tools](https://github.com/asyncapi/website/pull/5534) <sub>[#5534](https://github.com/asyncapi/website/pull/5534)</sub>

<sub><strong>Merged</strong> on Jun 2, 2026</sub>

- **Changes:** <code>+1</code> <code>-1</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

Updates the tool documentation link on the tools page to point to the correct documentation path in the community repository.

### Changes:
- Updated tool documentation URL from https://github.com/asyncapi/community/blob/master/new-tool-documentation.md to  https://github.com/asyncapi/community/blob/master/docs/040-guides/add-new-asyncapi-tool-to-website.md
- The previous link was pointing to an outdated or incorrect path. The new link directs users to the proper guide for adding new AsyncAPI tools to the website.

ref  : https://github.com/asyncapi/website/issues/5465#issuecomment-4582981458 - Issue - 10






## Summary by CodeRabbit

* **Documentation**
  * Updated the Tool Documentation link to reference the current guides location.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [redesigned-reminder-card-dark-mode](https://github.com/asyncapi/website/pull/5533) <sub>[#5533](https://github.com/asyncapi/website/pull/5533)</sub>

<sub><strong>Merged</strong> on Jun 2, 2026</sub>

- **Changes:** <code>+5</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Redesigned the reminder card to improve styling and support for dark mode.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| **Light** | <img width="995" height="656" alt="Light Theme Before" src="https://github.com/user-attachments/assets/9309f399-fce0-4b21-b3c0-6297ac99ad8e" /> | <img width="995" height="656" alt="Light Theme After" src="https://github.com/user-attachments/assets/62cc3bb4-0a04-45d7-ac9b-3d14ec771234" /> |
| **Dark** | <img width="997" height="660" alt="Dark Theme Before" src="https://github.com/user-attachments/assets/8139d6f3-995c-46b6-bf4a-ede1a7f6c2ce" /> | <img width="990" height="662" alt="Dark Theme After" src="https://github.com/user-attachments/assets/0a7b8c06-2d36-4f75-b461-2749dc18fddb" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5531--asyncapi-website.netlify.app/docs/reference
2. Locate the reminder card.
3. Toggle between the light and dark themes to verify the styling updates.

**Related issue(s)**


## Summary by CodeRabbit

* **Style**
  * Updated the Remember component’s dark-mode visuals: adjusted the main container background and refined the heading border to improve visual consistency and legibility in dark theme.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [enhance dark theme support for Visualizer and DocsLayout components](https://github.com/asyncapi/website/pull/5507) <sub>[#5507](https://github.com/asyncapi/website/pull/5507)</sub>

<sub><strong>Merged</strong> on May 31, 2026</sub>

- **Changes:** <code>+143</code> <code>-5</code> across 4 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

## Description

- Adds dark theme support for the AsyncAPI Specification Explorer pages.
- Applies existing docs dark-theme styling to explorer routes such as `/docs/reference/specification/v3.1.0-explorer`.
- Adds scoped dark-mode overrides for Schyma/React Flow generated elements, including nodes, side panel, tables, tabs, controls, and JSON examples.
- Keeps light theme behavior unchanged by relying on Schyma's default styles.
- Adds a narrow TypeScript declaration for `schyma/dist/esm/style.css`.

---

## Reproduction Guidelines

1. Open the Specification Explorer page:

- https://deploy-preview-5507--asyncapi-website.netlify.app/docs/reference/specification/v3.1.0-explorer

2. Test in light theme:

   - Confirm the explorer keeps the existing light appearance.
   - Confirm schema nodes, the side panel, tables, tabs, and JSON examples render correctly.

3. Switch to dark theme.

4. Test in dark theme:

   - Confirm the explorer background follows the docs dark theme.
   - Confirm all schema nodes are readable.
   - Confirm the side panel uses dark colors.
   - Confirm Examples/JSON blocks use dark code styling.
   - Confirm the docs menu popover remains readable.

---

## Screenshots

### Light Theme Comparison

| Before | After |
|---|---|
| <img width="700" alt="Light Theme Before 01" src="https://github.com/user-attachments/assets/038a8cac-7f79-425e-b30e-f05b469df0ca" /> | <img width="700" alt="Light Theme After 01" src="https://github.com/user-attachments/assets/038a8cac-7f79-425e-b30e-f05b469df0ca" /> |
| <img width="700" alt="Light Theme Before 02" src="https://github.com/user-attachments/assets/ecad2cd0-6bc3-446d-a917-b7819ae0d88c" /> | <img width="700" alt="Light Theme After 02" src="https://github.com/user-attachments/assets/ecad2cd0-6bc3-446d-a917-b7819ae0d88c" /> |

---

### Dark Theme Comparison

| Before | After |
|---|---|
| <img width="700" alt="Dark Theme Before 01" src="https://github.com/user-attachments/assets/32252af2-36da-4d72-a94c-095cd9447bf5" /> | <img width="700" alt="Dark Theme After 01" src="https://github.com/user-attachments/assets/3cf54e04-eb8a-496a-8e19-298c98aa196b" /> |
| <img width="700" alt="Dark Theme Before 02" src="https://github.com/user-attachments/assets/824c5916-faa6-42d3-be3c-50b856657ff5" /> | <img width="700" alt="Dark Theme After 02" src="https://github.com/user-attachments/assets/8b2419a5-0fee-45ee-a607-ac10ec6dbd92" /> |



## Summary by CodeRabbit

* **Style**
  * Enhanced dark-mode styling across the docs UI and schema visualizer.
  * Improved explorer/menu visuals with updated dark backgrounds, borders, text, and interactive (hover/focus) states.
  * Refined visualizer theming for panels, nodes, controls, tabs, tables, and code examples, including consistent code-block backgrounds and syntax highlighting.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [dark theme text issues in generator-api-section](https://github.com/asyncapi/website/pull/5525) <sub>[#5525](https://github.com/asyncapi/website/pull/5525)</sub>

<sub><strong>Merged</strong> on May 31, 2026</sub>

- **Changes:** <code>+16</code> <code>-1</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Fixed UI issues regarding text visibility in the dark theme for the `generator-api-section`.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| **Light** | <img width="936" height="259" alt="Light Theme Before" src="https://github.com/user-attachments/assets/c3bdd71b-d607-456c-8d80-a589964dd54b" /> | <img width="982" height="374" alt="Light Theme After" src="https://github.com/user-attachments/assets/d25bb098-c725-4ccb-a4eb-172090968698" /> |
| **Dark** | <img width="949" height="264" alt="Dark Theme Before" src="https://github.com/user-attachments/assets/3aa02334-ddc5-49af-81cf-6eb9e9779383" /> | <img width="973" height="395" alt="Dark Theme After" src="https://github.com/user-attachments/assets/c740805c-0764-4eae-92c8-03b5303dc16b" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5525--asyncapi-website.netlify.app/docs/tools/generator/api
2. Toggle between the light and dark themes to verify the text visibility is fixed.

**Related issue(s)**



## Summary by CodeRabbit

* **New Features**
  * Added support for rendering definition lists in MDX content with proper formatting and styling.

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [add dark mode support to newsroom article cards and dates](https://github.com/asyncapi/website/pull/5526) <sub>[#5526](https://github.com/asyncapi/website/pull/5526)</sub>

<sub><strong>Merged</strong> on May 31, 2026</sub>

- **Changes:** <code>+2</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Added dark mode support to newsroom article cards and dates.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| **Dark** | <img width="1234" height="479" alt="Dark Theme Before" src="https://github.com/user-attachments/assets/c1c8ff83-4af3-482f-85f0-85d27d6a40e2" /> | <img width="1233" height="497" alt="Dark Theme After" src="https://github.com/user-attachments/assets/e470d5bf-cf03-4403-a0f3-a421c35be8da" /> |
| **Light** | <img width="1235" height="413" alt="Light Theme Before" src="https://github.com/user-attachments/assets/ea901263-61ed-47f7-932c-a33b710da1f3" /> | <img width="1222" height="459" alt="Light Theme After" src="https://github.com/user-attachments/assets/705e9aa7-2044-407a-a4f6-9945de312f55" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5253--asyncapi-website.netlify.app/community/newsroom
2. Toggle between the light and dark themes to verify the styling updates for the article cards and dates.

**Related issue(s)**

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [improve OpenAPI comparison diagram dark mode styling](https://github.com/asyncapi/website/pull/5513) <sub>[#5513](https://github.com/asyncapi/website/pull/5513)</sub>

<sub><strong>Merged</strong> on May 30, 2026</sub>

- **Changes:** <code>+662</code> <code>-511</code> across 11 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Refactored OpenAPI comparison diagrams to follow the shared comparison component pattern.
- Replaced repeated inline hover handling with the reusable `HoverBox` component.
- Moved shared comparison helpers into `components/ComparisonCommon.tsx`.
- Updated OpenAPI comparison layouts to use shared `Column`, `HoverBox`, `StaticBox`, `ComponentGrid`, and `ComponentItem` patterns.
- Improved dark mode styling for borders, backgrounds, and hover states.
- Preserved existing OpenAPI comparison test IDs to avoid changing test behavior.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| Light | <img width="1010" height="733" alt="Screenshot Light Before" src="https://github.com/user-attachments/assets/8e312ff2-d5e5-4902-ac74-3d60515eeb03" /> | <img width="1002" height="742" alt="Screenshot Light After" src="https://github.com/user-attachments/assets/71eecc0b-feec-4a1c-bd76-3bf40cb2a5f9" /> |
| Dark | <img width="1048" height="743" alt="Screenshot Dark Before" src="https://github.com/user-attachments/assets/0989a618-7ce0-4b49-a5b7-ae5ab738e006" /> | <img width="1022" height="734" alt="Screenshot Dark After" src="https://github.com/user-attachments/assets/b42b84e9-fb16-494c-828b-ad8649389e4d" /> |

**Related issue(s)**



## Summary by CodeRabbit

* **Refactor**
  * Enhanced hover-driven comparison UI across AsyncAPI and OpenAPI views with improved visual interaction patterns.
  * Restructured comparison layout using shared UI components for consistent styling and behavior across comparison panels.
  * Updated AsyncAPI 3.0 operations section with nested hover interactions for better information navigation.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5513?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [enhance dark mode support and improve UI elements across tools](https://github.com/asyncapi/website/pull/5522) <sub>[#5522](https://github.com/asyncapi/website/pull/5522)</sub>

<sub><strong>Merged</strong> on May 30, 2026</sub>

- **Changes:** <code>+65</code> <code>-31</code> across 6 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Improved dark theme styles for the tools filter panel, including dropdown inputs, selected dropdown rows, applied filter chips, and ownership toggle.
- Updated info popovers and badge tooltip styling so content is readable in dark mode and no longer clips or overflows awkwardly.
- Fixed tools card header layout so the Open Source/Commercial badge stays aligned with the title without overlapping long titles.

**Screenshots**

| Theme | Feature | Before | After |
| --- | --- | --- | --- |
| **Light** | Filter View | <img width="359" height="722" alt="Light Filter Before" src="https://github.com/user-attachments/assets/1e0e6fe7-8626-4a8f-b734-0436a22cd431" /> | <img width="349" height="732" alt="Light Filter After" src="https://github.com/user-attachments/assets/49b66165-04bf-4362-bdb2-0b60090634ab" /> |
| **Light** | Tooltip | <img width="407" height="458" alt="Light Tooltip Before" src="https://github.com/user-attachments/assets/8ce68765-30f9-47cd-b445-74d6f0e4fefd" /> | <img width="399" height="451" alt="Light Tooltip After" src="https://github.com/user-attachments/assets/2fd2d949-7f1e-4f0f-bc7c-1041a03f33ed" /> |
| **Light** | Explanation Mark Hover | <img width="394" height="456" alt="Light Hover Before" src="https://github.com/user-attachments/assets/63d4b7d9-f4c2-4b9c-9c44-b64cae7265fb" /> | <img width="394" height="460" alt="Light Hover After" src="https://github.com/user-attachments/assets/ff9bf41e-e021-4955-821c-1f5186a6885f" /> |
| **Light** | Open Source Badge | <img width="440" height="472" alt="Light Badge Before" src="https://github.com/user-attachments/assets/e429c652-a488-48ef-8120-9745d784e4d2" /> | <img width="435" height="468" alt="Light Badge After" src="https://github.com/user-attachments/assets/0f29a33e-6b8e-462b-8877-5715aa278e39" /> |
| **Dark** | Filter View | <img width="370" height="740" alt="Dark Filter Before" src="https://github.com/user-attachments/assets/e06230ec-0237-4c00-bbd7-eca209e85eb2" /> | <img width="359" height="730" alt="Dark Filter After" src="https://github.com/user-attachments/assets/ec0f1ac2-b010-4bae-a968-b5370808b637" /> |
| **Dark** | Tooltip | <img width="400" height="486" alt="Dark Tooltip Before" src="https://github.com/user-attachments/assets/7b51e63b-d2d7-451a-a8bd-e163507521ab" /> | <img width="401" height="481" alt="Dark Tooltip After" src="https://github.com/user-attachments/assets/a484c11f-7885-4513-b7e5-b0a553b40500" /> |
| **Dark** | Explanation Mark Hover | <img width="401" height="455" alt="Dark Hover Before" src="https://github.com/user-attachments/assets/53cd29f2-a867-4c62-8639-9c85969185e9" /> | <img width="400" height="455" alt="Dark Hover After" src="https://github.com/user-attachments/assets/9643074b-34a5-4642-b5db-e2bec79029f8" /> |
| **Dark** | Open Source Badge | <img width="398" height="463" alt="Dark Badge Before" src="https://github.com/user-attachments/assets/c2f5ca62-9819-4c84-a0d0-30d2a1913db5" /> | <img width="425" height="448" alt="Dark Badge After" src="https://github.com/user-attachments/assets/b68874d6-ff04-435a-98cb-b93235e98c90" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5522--asyncapi-website.netlify.app/tools
2. Click on filters and apply them in both the dark and light themes.
3. Check the tool cards and hover behaviors to verify styling changes.

**Related issue(s)**

- Ref: https://github.com/asyncapi/website/pull/5253#issuecomment-4578167312


## Summary by CodeRabbit

* **Style**
  * Improved dark-mode colors, contrast and visual consistency across filters, cards, chips, toggles and buttons
  * Refined hover, focus and active states for interactive elements and badges
  * Adjusted card and chip spacing and visual hierarchy for cleaner layouts
* **Refactor**
  * Filter options made keyboard-focusable and standardized for more reliable interaction
  * Tooltips/popovers and description panels restyled with improved positioning, sizing and scroll behavior



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5522?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [mermaid dark theme ](https://github.com/asyncapi/website/pull/5512) <sub>[#5512](https://github.com/asyncapi/website/pull/5512)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+98</code> <code>-33</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

ref - https://github.com/asyncapi/website/pull/5253#issuecomment-4533042338
## Description

* Adds dark theme support for Mermaid diagrams rendered from MDX code blocks.
* Reinitializes Mermaid with light or dark theme variables based on the `html.dark` class.
* Re-renders Mermaid diagrams when the site theme changes, while keeping the initial render hydration-safe.

## Screenshots

| Theme | Before | After |
| :--- | :--- | :--- |
| **Light Theme** | <img width="969" height="468" alt="Screenshot 2026-05-29 at 01 23 21" src="https://github.com/user-attachments/assets/fe4e999e-7938-4c6f-aa91-805b1f8902a2" /> | <img width="969" height="468" alt="Screenshot 2026-05-29 at 01 23 21" src="https://github.com/user-attachments/assets/fe4e999e-7938-4c6f-aa91-805b1f8902a2" /> |
| **Dark Theme** | <img width="1000" height="576" alt="Screenshot 2026-05-29 at 01 16 05" src="https://github.com/user-attachments/assets/b27701fa-bedf-49a1-9c7e-f08590ef5572" /> | <img width="963" height="542" alt="Screenshot 2026-05-29 at 01 15 38" src="https://github.com/user-attachments/assets/b0c0638d-e65b-472a-b1c1-701ef003d704" /> |

## Steps to Reproduce

1. Navigate to the Deploy Preview: [https://deploy-preview-5512--asyncapi-website.netlify.app/docs/guides/message-validation](https://deploy-preview-5512--asyncapi-website.netlify.app/docs/guides/message-validation)
2. Check the diagrams by toggling between light and dark themes.
3. Resize the viewport to ensure the diagrams render correctly across different screen sizes.



## Summary by CodeRabbit

* **Bug Fixes**
  * Mermaid diagrams now properly display in light and dark modes, automatically adapting to your current site theme preference
  * Diagrams update dynamically when you switch between light and dark themes, ensuring consistent visual appearance



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5512?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [add dark mode text color to Remember component](https://github.com/asyncapi/website/pull/5516) <sub>[#5516](https://github.com/asyncapi/website/pull/5516)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+7</code> <code>-3</code> across 3 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

Improved the UI styling for the generate code tutorial page. 

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| Dark | <img width="967" height="462" alt="Screenshot Dark Before" src="https://github.com/user-attachments/assets/91d7eac2-e22f-4551-b2dc-9363676c435f" /> | <img width="991" height="467" alt="Screenshot Dark After" src="https://github.com/user-attachments/assets/d932c281-0dd1-492e-9abe-61f2e116364b" /> |
| Light | <img width="983" height="525" alt="Screenshot Light Before" src="https://github.com/user-attachments/assets/759d4f62-581a-4ad1-a4d5-712d42b17a9b" /> | <img width="983" height="525" alt="Screenshot Light After" src="https://github.com/user-attachments/assets/1b457fef-c4c9-4d21-8658-dcd21513a615" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5516--asyncapi-website.netlify.app/docs/tutorials/generate-code
2. Observe the UI changes by toggling between the light and dark themes.

**Related issue(s)**

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [add dark theme support for Warning component](https://github.com/asyncapi/website/pull/5517) <sub>[#5517](https://github.com/asyncapi/website/pull/5517)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+10</code> <code>-4</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- Enhanced the design of the warning components in the Roadmap section.

**Screenshots**

| Theme | Before | After |
| --- | --- | --- |
| Light | <img width="646" height="204" alt="Screenshot Light Before" src="https://github.com/user-attachments/assets/d95539fc-4dd9-494e-b23d-82ce5d9bf6fd" /> | <img width="714" height="206" alt="Screenshot Light After" src="https://github.com/user-attachments/assets/e30575dc-fdb9-4fd8-a443-be7c3f7abc4b" /> |
| Dark | <img width="635" height="174" alt="Screenshot Dark Before" src="https://github.com/user-attachments/assets/e3206a41-ab7a-491c-9b93-a3ad43c9e8e8" /> | <img width="723" height="215" alt="Screenshot Dark After" src="https://github.com/user-attachments/assets/22f5f3ae-2005-41e1-9758-f29903fb558f" /> |

**Reproduce**

1. Navigate to https://deploy-preview-5517--asyncapi-website.netlify.app/roadmap
2. Scroll down to see the warning component.
3. Test the UI by toggling between the light and dark themes.

**Related issue(s)**
- N/A

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [align netlify badge for mobile layout and remove stray margins](https://github.com/asyncapi/website/pull/5518) <sub>[#5518](https://github.com/asyncapi/website/pull/5518)</sub>

<sub><strong>Merged</strong> on May 29, 2026</sub>

- **Changes:** <code>+2</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

**Description**

- align netlify badge for mobile layout and remove stray margins


 **Please check the alignments in footer**
- Before 
<img width="376" height="296" alt="Screenshot 2026-05-29 at 14 35 15" src="https://github.com/user-attachments/assets/fb0d0df8-d4e6-47a7-8767-d04c02cabcb3" />

- After 
<img width="379" height="298" alt="Screenshot 2026-05-29 at 14 34 52" src="https://github.com/user-attachments/assets/b8ad609f-551e-4289-ba0e-bdcdaf4ffe7c" />


**Related issue(s)**

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [improve dark mode styles for AsyncAPI v3 comparison components](https://github.com/asyncapi/website/pull/5499) <sub>[#5499](https://github.com/asyncapi/website/pull/5499)</sub>

<sub><strong>Merged</strong> on May 28, 2026</sub>

- **Changes:** <code>+579</code> <code>-433</code> across 8 files
- **Language:** TypeScript
- **Merged by:** [@princerajpoot20](https://github.com/princerajpoot20)


<details>
<summary>View PR description</summary>

ref - https://github.com/asyncapi/website/pull/5253#issuecomment-4556732392

## Description

- Updated AsyncAPI v3 migration comparison components to support dark mode styling.
- Added dark mode classes for borders, backgrounds, text colors, and hover states.
- Improved readability and visual consistency of comparison diagrams on the v3 migration docs page.

## Screenshots

### Before : Dark theme

<img width="983" height="219" alt="Screenshot 2026-05-27 at 22 56 40" src="https://github.com/user-attachments/assets/04ca67ba-d751-48d4-8f89-e6308f7bbd74" />

<img width="978" height="279" alt="Screenshot 2026-05-27 at 22 56 46" src="https://github.com/user-attachments/assets/d9c47129-2a19-4d2e-a17f-45c29495a9c4" />

<img width="974" height="271" alt="Screenshot 2026-05-27 at 22 57 07" src="https://github.com/user-attachments/assets/719f8fbc-9fcc-46e0-8177-c3005d3f0f7e" />

<img width="960" height="551" alt="Screenshot 2026-05-27 at 22 57 31" src="https://github.com/user-attachments/assets/e4ccd937-4d9a-4b74-884d-1aa1d1144aa6" />

### After : Dark theme

<img width="971" height="211" alt="Screenshot 2026-05-27 at 22 54 18" src="https://github.com/user-attachments/assets/4686b1e9-a8d8-4211-9d71-d9c5bad177b5" />

<img width="978" height="264" alt="Screenshot 2026-05-27 at 22 54 24" src="https://github.com/user-attachments/assets/ca98a1eb-68d3-4560-b127-6913c99c5e44" />

<img width="967" height="701" alt="Screenshot 2026-05-27 at 22 54 32" src="https://github.com/user-attachments/assets/826b0b35-2f2a-42de-ac9b-0c64a6228082" />

<img width="966" height="257" alt="Screenshot 2026-05-27 at 22 54 41" src="https://github.com/user-attachments/assets/a33c154e-aea5-427b-a156-eb5bf87244b3" />

<img width="968" height="262" alt="Screenshot 2026-05-27 at 22 54 48" src="https://github.com/user-attachments/assets/f978cbf7-70bb-4732-8f03-da81f5ca9286" />

<img width="982" height="387" alt="Screenshot 2026-05-27 at 22 54 57" src="https://github.com/user-attachments/assets/c4dc5bb3-a7a6-4ae0-8750-0be0964be14b" />

<img width="986" height="587" alt="Screenshot 2026-05-27 at 22 55 05" src="https://github.com/user-attachments/assets/65e0a95c-6727-4d55-9d94-d3d9f5fed2f5" />

## Reproduce Guide

Navigate to:

https://deploy-preview-5499--asyncapi-website.netlify.app/docs/migration/migrating-to-v3

1. Switch the website to dark mode.
2. Scroll to the comparison sections on the page.
3. Hover over the interactive comparison boxes to verify their dark mode hover states.

## Related issue(s)

- https://github.com/asyncapi/website/pull/5253#issuecomment-4556732392


## Summary by CodeRabbit

* **New Features**
  * Added reusable comparison panels and a generic hover-enabled tile component used across AsyncAPI comparisons.
* **Refactor**
  * Consolidated many comparison views onto the shared components, unifying hover behavior, focus handling, and interaction wiring.
* **Style**
  * Expanded dark-mode styling and refined hover/active visuals across channels, operations, parameters, servers, metadata, schema, and ID/address comparisons.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5499?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [improve TSCMemberCard responsiveness by adjusting layout and conditionally displaying availability badge on mobile](https://github.com/asyncapi/website/pull/5502) <sub>[#5502](https://github.com/asyncapi/website/pull/5502)</sub>

<sub><strong>Merged</strong> on May 28, 2026</sub>

- **Changes:** <code>+9</code> <code>-4</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

## Description

- Improved `TSCMemberCard` responsiveness for mobile devices.
- Adjusted the card layout to better align content across different screen sizes.
- Added responsive alignment changes using `items-center sm:items-start`.
- Prevented avatar shrinking on smaller screens with `shrink-0`.
- Conditionally displayed the availability badge differently on mobile and desktop for improved readability and spacing.
- Ensured the component works consistently in both light and dark themes.

## Before

### Light Theme
<img width="380" height="671" alt="Screenshot 2026-05-28 at 10 04 09" src="https://github.com/user-attachments/assets/21f93904-4204-40d7-8c55-076c0a612feb" />

### Dark Theme

<img width="378" height="668" alt="Screenshot 2026-05-28 at 10 04 15" src="https://github.com/user-attachments/assets/2e722042-0329-4abe-b52e-c3bcbf233e0e" />

## After

### Light Theme

<img width="380" height="671" alt="Screenshot 2026-05-28 at 10 03 44" src="https://github.com/user-attachments/assets/8f0fc8df-34df-4cd0-a8e4-d643fd17dac3" />

### Dark Theme

<img width="375" height="669" alt="Screenshot 2026-05-28 at 10 03 51" src="https://github.com/user-attachments/assets/812ae256-590d-4e01-a885-84e03e4e136b" />

## Reproduction Guidelines

1. Open the community/team members page.https://deploy-preview-5502--asyncapi-website.netlify.app/community/tsc
2. Resize the browser window to a mobile viewport or use browser device emulation.
3. Observe the `TSCMemberCard` layout before applying the fix:
   - Avatar and text alignment appear inconsistent on smaller screens.
   - Availability badge affects spacing and responsiveness.
4. Apply the changes from this PR.
5. Recheck the component in both light and dark themes across mobile and desktop screen sizes.
6. Verify:
   - Proper alignment of member details.
   - Avatar remains fixed without shrinking.
   - Availability badge displays correctly depending on screen size.
   - No visual regressions in dark mode.
## Related issue(s)

Fixes N/A

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [enhance dark theme support and improve styling c…](https://github.com/asyncapi/website/pull/5477) <sub>[#5477](https://github.com/asyncapi/website/pull/5477)</sub>

<sub><strong>Merged</strong> on May 27, 2026</sub>

- **Changes:** <code>+5</code> <code>-3</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

Ref: https://github.com/asyncapi/website/pull/5253#issuecomment-4532416854

**Description**

- Fixed dark theme styling for the mobile docs sidebar.
- Updated the mobile docs menu background and search button to use existing dark theme classes.
- Kept the change scoped to `DocsMobileMenu` without adding global CSS or new colors.

**Steps to Reproduce**

1. Open the website in a mobile viewport.
2. Enable dark mode from the navbar theme toggle.
3. Navigate to any docs page.
4. Tap the docs sidebar/menu button near the top of the docs page.
5. Notice that the mobile docs sidebar and search bar still appear in light theme colors.

**Before**

<img width="317" height="596" alt="Screenshot 2026-05-25 at 13 23 28" src="https://github.com/user-attachments/assets/fb80bfb0-3dd3-4972-907c-7fab709b7210" />

**After**

<img width="379" height="671" alt="Screenshot 2026-05-25 at 13 22 57" src="https://github.com/user-attachments/assets/297d71f3-d492-4a8c-ab77-d047bb1a9c50" />

**Related issue(s)**

Fixes #5253



## Summary by CodeRabbit

## Style
* Enhanced dark mode styling for navigation dropdown arrows with updated hover effects.
* Improved dark mode appearance for mobile menu, including background colors and search button styling.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5477?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [align mobile docs dropdown icon styles](https://github.com/asyncapi/website/pull/5486) <sub>[#5486](https://github.com/asyncapi/website/pull/5486)</sub>

<sub><strong>Merged</strong> on May 26, 2026</sub>

- **Changes:** <code>+2</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

refs: https://github.com/asyncapi/website/pull/5253#issuecomment-4534746423
**Description**

- Fixed inconsistent icon styling in the mobile Docs dropdown menu.
- Updated the mobile Docs dropdown to use the same `buckets` data as the desktop Docs dropdown.
- Kept the change minimal and scoped to `MobileNavMenu`.

**Steps to Reproduce**

1. Open the website on a mobile viewport.
2. Open the navbar menu.
3. Expand the Docs dropdown.
4. Notice that the Docs dropdown icons use a different purple style compared to the desktop Docs dropdown.

**Screenshots**

Before:
<img width="374" height="665" alt="Screenshot 2026-05-26 at 09 54 52" src="https://github.com/user-attachments/assets/61bbed42-e3dc-492f-a88d-d5d08512998c" />
<img width="377" height="672" alt="Screenshot 2026-05-26 at 10 06 38" src="https://github.com/user-attachments/assets/a04bdb9f-ff7c-4f51-b65d-a879d2325a92" />


After:
<img width="400" height="685" alt="Screenshot 2026-05-26 at 09 55 37" src="https://github.com/user-attachments/assets/8f1485b3-8f80-472d-9d59-a884d907142f" />
<img width="384" height="666" alt="Screenshot 2026-05-26 at 09 56 18" src="https://github.com/user-attachments/assets/429708bf-1b6e-4218-81be-000cdc5be417" />


**Related issue(s)**

Fixes https://github.com/asyncapi/website/pull/5253#issuecomment-4534746423

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [update scroll-to-top button hover background color and improve image styling for dark mode](https://github.com/asyncapi/website/pull/5484) <sub>[#5484](https://github.com/asyncapi/website/pull/5484)</sub>

<sub><strong>Merged</strong> on May 26, 2026</sub>

- **Changes:** <code>+2</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

## Description

Ref: https://github.com/asyncapi/website/pull/5253#issuecomment-4539882638

- Added dark theme support for the scroll-to-top button.
- Replaced the hardcoded hover background color with an existing theme color for better consistency.
- Updated the scroll arrow icon styling so it remains visible in dark mode.

### Before applying fixes
The scroll-to-top button had visibility and hover styling issues in dark theme.

<img width="376" height="666" alt="Screenshot 2026-05-25 at 21 38 23" src="https://github.com/user-attachments/assets/9fff5f60-c4bf-49b8-9f40-dd246a2f8886" />

### After applying fixes

<img width="378" height="677" alt="Screenshot 2026-05-25 at 21 42 20" src="https://github.com/user-attachments/assets/1341d5fc-31a7-44dd-b625-bcbcb7bd484c" />

## Related issue(s)

- N/A

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [enhance dark theme support in search and navigation components](https://github.com/asyncapi/website/pull/5471) <sub>[#5471](https://github.com/asyncapi/website/pull/5471)</sub>

<sub><strong>Merged</strong> on May 26, 2026</sub>

- **Changes:** <code>+43</code> <code>-26</code> across 3 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

## Description

- Updated the mobile docs search button to support dark theme using existing theme classes.
- Added `data-theme="dark"` alongside the existing `dark` class so Algolia DocSearch uses its dark theme.
- Wrapped the DocSearch modal with existing dark text styling to keep no-results text readable in dark mode.

### New behaviour

<video src="https://github.com/user-attachments/assets/53b86845-e2c5-4e38-99e4-519347e812ea" controls width="100%"></video>

## Related issue(s)

Fixes #5470



## Summary by CodeRabbit

* **Style**
  * Enhanced dark mode styling consistency across search modal, mobile navigation, and theme components.

* **Bug Fixes**
  * Improved dark mode theme synchronization to ensure proper styling persistence and visual consistency.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5471?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [improve docs callout dark theme](https://github.com/asyncapi/website/pull/5479) <sub>[#5479](https://github.com/asyncapi/website/pull/5479)</sub>

<sub><strong>Merged</strong> on May 25, 2026</sub>

- **Changes:** <code>+4</code> <code>-4</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/144201791?u=bee7a229b7ad0dd54d22bf6acd2525ae3c6a4537&v=4" width="24" height="24" align="absmiddle" alt="Sourya07" title="Sourya07"> <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

ref :https://github.com/asyncapi/website/pull/5253#issuecomment-4532677110
ref :https://github.com/asyncapi/website/pull/5253#issuecomment-4532649920
**Description**

- Fixed dark theme styling for the release notes callout in the docs layout.
- Updated the release notes callout background and text to use existing dark theme classes.
- Fixed alignment of the plus icon in the roadmap page “Join Our Community” button.
- Kept the changes scoped to `components/layout/DocsLayout.tsx` and `pages/roadmap.tsx`.

- Before

<img width="983" height="164" alt="Screenshot 2026-05-25 at 14 12 24" src="https://github.com/user-attachments/assets/0a7737ed-9148-4df3-90d0-3fe5227ed812" />
<img width="630" height="259" alt="Screenshot 2026-05-25 at 14 13 29" src="https://github.com/user-attachments/assets/e043e542-2a87-4322-bfb9-cf32a55cf2c0" />


- After 

<img width="974" height="126" alt="Screenshot 2026-05-25 at 14 12 12" src="https://github.com/user-attachments/assets/16bb8125-a697-446c-b3e7-ef93299414de" />
<img width="606" height="312" alt="Screenshot 2026-05-25 at 14 13 15" src="https://github.com/user-attachments/assets/70150de2-aa22-4138-af0f-1a944d2285da" />



**Related issue(s)**

Fixes #5253



## Summary by CodeRabbit

* **Style**
  * Improved dark mode appearance for the release notes section with updated background and text color styling.
  * Updated icon sizing and responsive behavior for the "Join Our Community" button.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5479?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [enhance dark theme support for CLI page components](https://github.com/asyncapi/website/pull/5482) <sub>[#5482](https://github.com/asyncapi/website/pull/5482)</sub>

<sub><strong>Merged</strong> on May 25, 2026</sub>

- **Changes:** <code>+8</code> <code>-6</code> across 2 files
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

Fixes : https://github.com/asyncapi/website/pull/5253#issuecomment-4533246868
**Description**

- Added dark theme support for the CLI tools page.
- Updated the features section, feature icon cards, and inline command snippet to use existing dark theme classes.
- Applied the same styling to both localized and non-localized CLI routes.

- Before 
<img width="1233" height="641" alt="Screenshot 2026-05-25 at 15 17 19" src="https://github.com/user-attachments/assets/4eb11705-f03e-4172-8012-52d630f34d62" />

- After 
<img width="1362" height="698" alt="Screenshot 2026-05-25 at 15 17 09" src="https://github.com/user-attachments/assets/66656cf8-1975-4535-90f1-b009737e0686" />


**Related issue(s)**

Fixes #5253




## Summary by CodeRabbit

* **Style**
  * Improved dark mode appearance across CLI tools documentation with enhanced styling for code elements and feature icons.



[![Review Change Stack](https://storage.googleapis.com/coderabbit_public_assets/review-stack-in-coderabbit-ui.svg)](https://app.coderabbit.ai/change-stack/asyncapi/website/pull/5482?utm_source=github_walkthrough&utm_medium=github&utm_campaign=change_stack)

</details>


---

#### <img src="https://raw.githubusercontent.com/primer/octicons/main/icons/git-merge-16.svg" width="16" height="16" align="absmiddle" alt="Merged" title="Merged pull request"> [update className for improved styling consistency](https://github.com/asyncapi/website/pull/5468) <sub>[#5468](https://github.com/asyncapi/website/pull/5468)</sub>

<sub><strong>Merged</strong> on May 24, 2026</sub>

- **Changes:** <code>+1</code> <code>-2</code> across 1 file
- **Language:** TypeScript
- **Approved by:** <img src="https://avatars.githubusercontent.com/u/44585452?u=fa0f6a137d8f8613707cc500dbbc19066be78bd8&v=4" width="24" height="24" align="absmiddle" alt="princerajpoot20" title="princerajpoot20">


<details>
<summary>View PR description</summary>

## Description

- Fixed the mobile hamburger menu not opening correctly on small screens.
- The issue was caused by `transform: translateZ(0)` being applied to the sticky navbar on all screen sizes. Since the mobile menu uses fixed positioning and is rendered inside the navbar, the transformed parent interfered with the mobile overlay behavior.
- Updated the `transform` and `will-change` styles to apply only on large screens using Tailwind responsive classes, preserving the existing desktop behavior while preventing the mobile menu issue on smaller devices.

## Related issue(s)

### Before
<video src="https://github.com/user-attachments/assets/bb12f0ed-2afe-4536-bde8-721467c553d4" controls width="100%"></video>

### After
<video src="https://github.com/user-attachments/assets/c031bd05-0f81-4e54-b17e-9b36d7d70e34" controls width="100%"></video>

Fixes #5469

</details>



---



---

<div align="center">

<sub>Last updated: June 7, 2026</sub>

<br/>

<sub>Generated by <a href="https://github.com/opensource-showcase/opensource-showcase">opensource-showcase</a> • View raw data: <a href="contributions.json">contributions.json</a></sub>

</div>
