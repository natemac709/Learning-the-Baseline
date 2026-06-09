# Contributing to Learning the Baseline

We welcome community contributions to help scale this analog behavioral framework. Because this system relies on absolute physical containment and unyielding focus, all contributions must adhere strictly to the defensive security parameters and engineering metrics outlined below. 

Think of these guidelines as a digital firewall protecting a quiet sanctuary—we keep the entry requirements tight so the baseline remains uncorrupted by digital noise or commercial optimization.

---

## Code of Conduct & Contribution Philosophy

Before opening a pull request (PR), understand our core operational stance:
* **The Project is Closed to Software Hooks:** We do not accept API integrations, analytics tracking, data collection scripts, or background webhooks. If a modification collects data, tracks a user, or connects to a cloud server, it violates the Project Charter and will be immediately closed.
* **No Contentiousness:** The open-source ledger operates as a fixed schedule of historical truth. The submission thread functions purely like a public transit schedule. No interactive debate, commentary, or ideological arguments are processed.

---

## Areas of Active Development

### 1. Hardware Chassis Modding (Prototype Iterations)
You can submit alternative mechanical blueprint designs (such as 3D printing STL files, CAD files, or CNC routing specifications) to help adapt the universal matte-slate casing to diverse physical desks.
* **Chassis Parameter Rule:** The physical viewport window must maintain the exact $1.50\text{"}$ Height $\times$ $4.50\text{"}$ Width mechanical cutout positioned precisely at the lower 33.3% vertical boundary coordinate of the physical enclosure.

### 2. Canvas Asset Submissions (`/assets/wallpaper/`)
You can submit fresh typographical layouts or visual arguments for the standalone desktop gallery or future mobile cards.
* **Mobile Asset Constraints:** Format must be `.png` only, at a strict $1290 \times 2796$ pixel canvas size. The layout requires a `#000000` True-Black background layer with pure `#FFFFFF` typography pinned strictly between vertical coordinates $y=1400$ and $y=1850$.
* **Desktop Asset Constraints:** Format must be `.png` only, using standard widescreen aspect ratios (e.g., 16:9). Designs must utilize extensive, clean negative canvas space around a centralized visual element to protect desktop icon organization.
* **Zero Metadata Clause:** Submissions must remain entirely clean of code brackets, artificial terminal box frames, system tracking index numbers, or corporate branding. Text must be presented in a clean, professional, and timeless typeface.

---

## Security & Submission Protocol

To protect the master branch from automated vulnerabilities or malicious file injection, all contributors must execute the following protocol:

1. **Fork and Branch:** Fork the repository and isolate your modifications within a clean feature branch:
   ```bash
   git checkout -b feature/YourSpecificChassisOrAssetMod
   ```
2. **Review Relative Paths:** If your contribution includes documentation edits, verify that all markdown link elements use direct internal file pointers (e.g., `guidance.md`). Unverified external web hyperlinks will be automatically flagged and rejected during review.
3. **Open a Pull Request:** Submit your PR against the master branch. In your pull request description, you must explicitly state:
   * A concise breakdown of your structural changes.
   * A formal validation statement explaining how your modification respects the Project Charter's constraints.
4. **Maintainer Authorization:** All merging requires manual review and sign-off by the repository owner. Branch protection rules are actively enforced on the `main` branch to block unapproved external pushes.
