## Fix 1: Improved Keyboard Focus Visibility(selected button)
**Before** (src/main/resources/templates/base.peb:L53-58):
   button[type="submit"],
   button {
    color: white !important; /* White text on blue background for better contrast */
    }

**After** (src/main/resources/templates/base.peb:L53-58):
button[type="submit"],
button {
    background-color: #f0f8ff !important; /* Dark text on light background for better contrast */color: #003366 !important;
    font-weight: 600 !important;
    }

Impact:Keyboard users can now clearly identify which button has focus(1.4.3 Contrast (Minimum) – Level AA &2.4.7Focus Visible)