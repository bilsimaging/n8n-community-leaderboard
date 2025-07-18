---
layout: content
title: Workflow ratings
permalink: /workflows/
show_last_updated: true
---

<p id="last-updated" class="text-muted"></p>


<!-- Modal for the chart -->
<div id="chartModal" class="modal">
    <div class="modal-content">
        <span class="close">&times;</span>
        <div id="chart-container">
            <svg class="line-chart"></svg>
            <div class="toggle-container">
                <label>
                    <input type="checkbox" id="dayCountToggle" data-umami-event="table_chart" data-umami-event-table="align"> Show Aligned Growth
                </label>
            </div>
        </div>
    </div>
</div>

<table id="stats-table" class="display compact">
    <thead>
        <tr>
            <th class="number-column"></th> <!-- Index column -->
            <th></th> <!-- Avatar column -->
            <th>Creator</th>
            <th>$</th>
            <th>Workflow Name</th>
            <th>Total Unique Views</th>
            <th>Total Unique Inserters</th>
            <th>Monthly Unique Views</th>
            <th>Monthly Unique Inserters</th>
            <th>Weekly Unique Views</th>
            <th>Weekly Unique Inserters</th>
            <th>Creation Date</th>
        </tr>
    </thead>
    <tbody>
    </tbody>
</table>

<link rel="stylesheet" href="{{ '/assets/css/modal.css' | relative_url }}">
<script src="https://cdn.jsdelivr.net/npm/chart.xkcd@1.1.13/dist/chart.xkcd.min.js"></script>
<script src="{{ '/assets/js/generate-table-workflows.js' | relative_url }}"></script>
<script src="{{ '/assets/js/workflow-chart.js' | relative_url }}"></script>
