# Problem: Won't boot, grub says "uuid does not exist"
sch: https://www.google.com/search?q=fedora+uuid+changed+won%27t+boot

# Solution:
https://discussion.fedoraproject.org/t/i-am-unable-to-bootup-fedora-38-dev-disk-by-uuid-does-not-exist/85585/3

# Solution: Disable "Intel RST = Rapid Storage Technology" in motherboard UEFI settings.
I had this problem from clearing my bios NVram. It reactivated "Intel RST" by default! Disable it to fix missing "uuid" in boot.
