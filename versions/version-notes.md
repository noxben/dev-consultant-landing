# Version History & Notes

## Version Tracking

Track different iterations of your landing page here. This helps you understand what changed and why.

---

## v2.0 - Current Version (February 2026)

**Status**: Active  
**File**: `index.html`

### Changes from v1:
- Initial production version
- Refined color palette for better contrast
- Optimized animations for performance
- Added intersection observer for scroll effects
- Improved mobile responsiveness

### Features:
- Hero section with gradient background
- Problem/solution narrative flow
- Four core service offerings
- Social proof with stats and logos
- Clear CTA throughout
- Smooth scroll navigation
- Responsive grid layouts

### Notes:
- Email and phone need to be updated with real contact info
- Organization logos are text-based placeholders
- Consider adding testimonials in future version

---

## v1.0 - Initial Draft

**Status**: Archived  
**File**: `versions/v1-consultant-landing.html`

### Features:
- Basic structure
- Initial content draft
- Simple styling

### Issues Fixed in v2:
- Color contrast improved
- Typography hierarchy refined
- Mobile layout issues resolved
- Animation performance optimized

---

## Version Naming Convention

Use semantic versioning for major updates:
- **Major (X.0)**: Complete redesigns or structural changes
- **Minor (1.X)**: New sections, significant content updates
- **Patch (1.1.X)**: Copy edits, bug fixes, small tweaks

### Examples:
- `v2.0` - Major redesign with new layout
- `v1.5` - Added testimonials section
- `v1.2.3` - Fixed mobile menu bug

---

## Planning Future Versions

### v2.1 (Planned)
- [ ] Add client testimonials section
- [ ] Integrate real organization logos
- [ ] Add case study previews
- [ ] Implement contact form

### v3.0 (Concept)
- [ ] Multi-page site with separate services pages
- [ ] Blog integration
- [ ] Resources/downloads section
- [ ] Dark mode option

---

## Changelog Template

When creating a new version, copy this template:

```
## vX.X - [Version Name] (Month Year)

**Status**: [Active/Archived/Draft]  
**File**: `versions/vX-description.html`

### Changes:
- 
- 
- 

### New Features:
- 
- 

### Bug Fixes:
- 
- 

### Notes:
- 
```

---

## Git Commit Strategy for Versions

### Small changes (patches):
```bash
git commit -m "fix: Correct phone number formatting"
git commit -m "content: Update service descriptions"
```

### Medium changes (minor versions):
```bash
git commit -m "feat: Add testimonials section"
git commit -m "style: Redesign hero with video background"
```

### Major changes:
```bash
git commit -m "BREAKING: Complete site redesign for v2.0"
```

Before major version changes, create a branch:
```bash
git checkout -b v3-redesign
# Make changes
git commit -m "Major redesign for v3.0"
git checkout main
git merge v3-redesign
```

---

## Backup Strategy

1. **Git history**: All versions tracked automatically
2. **Version folder**: Save major iterations as separate files
3. **GitHub**: Cloud backup of all versions
4. **Local backup**: Periodically backup entire project folder

---

## Recovery

To revert to a previous version:

```bash
# See all commits
git log --oneline

# Go back to specific commit (view only)
git checkout [commit-hash]

# Restore that version permanently
git revert [commit-hash]
# OR
git reset --hard [commit-hash]  # CAREFUL: loses all changes after this point
```

To restore from version folder:
```bash
cp versions/v1-consultant-landing.html index.html
git add index.html
git commit -m "Revert to v1 design"
```
