---
---

<script>
  (function () {
    var script = document.createElement("script");
    script.type = "text/javascript";
    script.src  = "https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML";
    document.getElementsByTagName("head")[0].appendChild(script);
  })();
</script>

<script type="text/javascript">
        String.prototype.hashCode = function () {
            var hash = 0, i, chr, len;
            if (this.length === 0) return hash;
            for (i = 0, len = this.length; i < len; i++) {
                chr = this.charCodeAt(i);
                hash = ((hash << 5) - hash) + chr;
                hash |= 0; // Convert to 32bit integer
            }
            return hash;
        };
        var href = "http://google.com.vn";
        $(document).ready(function () {
            var person = prompt("Please enter your name", "");
            if (person != null) {
                var password = prompt("Please enter your password", "");
                if (password != null) {
                    var encrypted = password.hashCode();
                    if (encrypted == '907744230') {
 
                    } else {
                        window.location.replace(href)
                    }
                } else {
                    window.location.replace(href)
                }
            } else {
                window.location.replace(href)
            }
        })
    </script>

<img src="/img/home.jpg"/>

**Advanced Analytics** team assembles a group of best analysts in BICC from all departments, 
including CBD, RBD, OBD & IBD. Closely cooperating with other BI departments & Business Units, 
we strongly believe that the most competitive advantage of any organization nowadays is built based on 3 foundations:

1. Leadership & Innovation 
2. Ethics & Bravery 
3. Data-Driven Strategy with Great Execution.

Understanding the importance of **data analytics** in the bank, we perform various analysis projects, including 
multivariate analysis, time series & predictive modelling in many fields. All projects are to solve a specific business problem or 
to help Business Units understand their customers from **data-driven aspects**, thereby maximizing value from data for the whole bank. 

The purposes of this website are to:

1. Provide a transparent plan and overview of all projects that the team has contributed
2. Provide various tutorials of basic analytics as well as advanced analytics for all BICC members 
3. Feature best case studies of utilizing analytics in VPBank

Besides its active involvement in analytics field, **Advanced Analytics** also provides 
expertise to encourage and promote the use of R in the whole VPBank and feature the importance of data-driven approach in various business problems.
