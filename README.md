## My Custom Pi-hole Blocklist

A centralized repository for managing local DNS blocks, trackers, and IoT telemetry for my Proxmox home lab.

---

### 🚀 Usage

To add this list to your Pi-hole:

1. Copy the **[Raw]** URL of the `hosts` file.
2. Navigate to **Pi-hole Admin > Adlists**.
3. Paste the URL and click **Add**.
4. Run `pihole -g` or **Update Gravity** in the dashboard.

### 📝 Format

Domains must be added using the `0.0.0.0` prefix for maximum compatibility:

```text
0.0.0.0 example-ad-domain.com
0.0.0.0 tracking-sdk-v1.net

```
