import React, { useState } from 'react';
import { 
  Users, 
  Building2, 
  Percent, 
  Calendar, 
  Download, 
  ChevronDown,
  Target,
  MailCheck,
  TrendingUp,
  Activity
} from 'lucide-react';

// --- MOCK DATA ---
const mockTableData = [
  { id: '0031i00000A1b2C', name: 'Alice Smith', account: 'TechCorp GmbH', status: 'Opted In', title: 'CTO', region: 'DACH', practice: 'AI' },
  { id: '0031i00000X9y8Z', name: 'Jean Dupont', account: 'Retail Cloud France', status: 'Pending', title: 'VP Engineering', region: 'France', practice: 'Data Analytics' },
  { id: '0031i00000M4n5O', name: 'Lars Jensen', account: 'Nordic Shippers', status: 'Opted Out', title: 'IT Director', region: 'Nordics', practice: 'Security' },
  { id: '0031i00000P7q8R', name: 'Emma Wilson', account: 'FinTech UK', status: 'Opted In', title: 'Data Scientist', region: 'UKI', practice: 'Data Analytics' },
  { id: '0031i00000K2l3M', name: 'Hans Gruber', account: 'AutoParts Berlin', status: 'Opted In', title: 'CEO', region: 'DACH', practice: 'Infrastructure' },
];

export default function App() {
  // State for interactivity
  const [activeRegionFilter, setActiveRegionFilter] = useState(null);
  const [activePracticeFilter, setActivePracticeFilter] = useState(null);
  const [trendGranularity, setTrendGranularity] = useState('Month');

  // Filtered table data based on chart clicks
  const filteredData = mockTableData.filter(row => {
    let match = true;
    if (activeRegionFilter && row.region !== activeRegionFilter) match = false;
    if (activePracticeFilter && row.practice !== activePracticeFilter) match = false;
    return match;
  });

  const clearFilters = () => {
    setActiveRegionFilter(null);
    setActivePracticeFilter(null);
  };

  return (
    <div className="min-h-screen bg-gray-50 font-sans text-gray-900">
      
      {/* SECTION 0: Global Filter Bar (PLX Controls) */}
      <div className="sticky top-0 z-10 bg-white border-b border-gray-200 flex flex-col shadow-sm">
        {/* Row 1: Time Controls & Export */}
        <div className="px-6 py-3 flex items-center justify-between border-b border-gray-100">
          <div className="flex items-center space-x-2 text-sm text-gray-500 font-medium">
             <span>Global Slicing Controls</span>
          </div>
          
          <div className="flex items-center space-x-4">
            {/* Time Range Picker */}
            <button className="flex items-center px-3 py-1.5 bg-white rounded-md text-sm text-gray-700 border border-gray-300 hover:bg-gray-50 transition-colors shadow-sm">
              <Calendar className="w-4 h-4 mr-2 text-gray-500" />
              Last 30 Days
              <ChevronDown className="w-4 h-4 ml-2 text-gray-400" />
            </button>
            
            <button className="p-1.5 text-gray-500 hover:text-gray-800 hover:bg-gray-100 rounded-md transition-colors" title="Export Dashboard">
              <Download className="w-5 h-5" />
            </button>
          </div>
        </div>

        {/* Row 2: Segment & Business Filters */}
        <div className="px-6 py-2.5 flex flex-wrap items-center gap-3 bg-gray-50/50 overflow-x-auto">
          
          {/* Core Segment Filters */}
          <FilterChip label="Segment" value="SMB" />
          
          {/* Marketability Toggle */}
          <button className="flex items-center px-3 py-1.5 bg-white border border-gray-300 rounded-full text-sm text-gray-700 hover:bg-gray-50 transition-colors shadow-sm shrink-0">
            <div className="w-7 h-4 bg-blue-600 rounded-full flex items-center p-0.5 mr-2 transition-colors">
              <div className="w-3 h-3 bg-white rounded-full shadow-sm translate-x-3"></div>
            </div>
            Marketable
          </button>
          
          <FilterChip label="Geography" value="EMEA > UK > GBR" />
          
          <div className="w-px h-5 bg-gray-300 mx-1"></div> {/* Divider */}
          
          {/* Strategic Business Filters */}
          <FilterChip label="Account Digital Native" value="All" />
          
          <FilterChip label="Practice Area" value="All (Inc. No Opp)" />
          <FilterChip label="Sub Region" value="All" />
        </div>
      </div>

      <div className="p-6 max-w-[1600px] mx-auto space-y-6">

        {/* SECTION 1: Executive Summary */}
        <div className="bg-white p-6 rounded-lg border border-gray-200">
          <h2 className="text-lg font-medium mb-6 flex items-center text-gray-800">
            <Target className="w-5 h-5 mr-2 text-blue-600" />
            Executive Summary
          </h2>
          
          <div className="grid grid-cols-1 md:grid-cols-4 gap-4 mb-6">
            <KpiCard title="Total Target Accounts" value="14,205" icon={<Building2 className="w-5 h-5" />} trend="+2.4%" />
            <KpiCard title="Total Database Contacts" value="48,932" icon={<Users className="w-5 h-5" />} trend="+5.1%" />
            <KpiCard title="Marketable Contacts" value="62.4%" icon={<MailCheck className="w-5 h-5" />} trend="+1.2%" trendPositive={true} />
            <KpiCard title="Account Reach" value="41.8%" icon={<Percent className="w-5 h-5" />} trend="-0.5%" trendPositive={false} />
          </div>

          <div className="grid grid-cols-1 lg:grid-cols-2 gap-4">
            {/* Marketability Mix */}
            <div className="bg-gray-50 p-6 rounded-lg border border-gray-100 flex flex-col">
              <h3 className="text-base font-medium text-gray-800 mb-6">Marketability Mix</h3>
              <div className="flex-1 flex items-center justify-center">
                {/* Mock Donut Chart via CSS/SVG */}
                <div className="relative w-40 h-40">
                  <svg viewBox="0 0 36 36" className="w-full h-full">
                    <path className="text-green-600" strokeDasharray="60, 100" d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="currentColor" strokeWidth="4" />
                    <path className="text-yellow-500" strokeDasharray="20, 100" strokeDashoffset="-60" d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="currentColor" strokeWidth="4" />
                    <path className="text-red-500" strokeDasharray="10, 100" strokeDashoffset="-80" d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="currentColor" strokeWidth="4" />
                    <path className="text-gray-200" strokeDasharray="10, 100" strokeDashoffset="-90" d="M18 2.0845 a 15.9155 15.9155 0 0 1 0 31.831 a 15.9155 15.9155 0 0 1 0 -31.831" fill="none" stroke="currentColor" strokeWidth="4" />
                  </svg>
                  <div className="absolute inset-0 flex flex-col items-center justify-center">
                    <span className="text-2xl font-normal text-gray-800">60%</span>
                    <span className="text-xs text-gray-500">Opted In</span>
                  </div>
                </div>
                <div className="ml-10 space-y-3 text-sm">
                  <LegendItem color="bg-green-600" label="Opted In" value="29k" />
                  <LegendItem color="bg-yellow-500" label="Pending" value="9k" />
                  <LegendItem color="bg-red-500" label="Opted Out" value="4k" />
                  <LegendItem color="bg-gray-200" label="No Status" value="6k" />
                </div>
              </div>
            </div>

            {/* Reach by Region */}
            <div className="bg-gray-50 p-6 rounded-lg border border-gray-100">
              <h3 className="text-base font-medium text-gray-800 mb-6">Account Reach % by Sub-Region</h3>
              <div className="space-y-5">
                <HorizontalBar label="DACH" percentage={55} color="bg-blue-600" />
                <HorizontalBar label="UKI" percentage={48} color="bg-blue-600" />
                <HorizontalBar label="Nordics" percentage={42} color="bg-blue-600" />
                <HorizontalBar label="France" percentage={31} color="bg-blue-600" />
                <HorizontalBar label="Benelux" percentage={24} color="bg-blue-600" />
              </div>
            </div>
          </div>
        </div>

        {/* SECTION 2: Regional Persona Gap Analysis */}
        <div className="bg-white p-6 rounded-lg border border-gray-200">
          <div className="mb-6 flex justify-between items-end">
            <div>
              <h3 className="text-base font-medium text-gray-800">Regional Persona Gap Analysis</h3>
              <p className="text-sm text-gray-500 mt-1">Select a region to view its specific persona mix and identify gaps.</p>
            </div>
            {activeRegionFilter && (
              <button onClick={() => setActiveRegionFilter(null)} className="text-sm text-blue-600 hover:text-blue-800 font-medium">
                Clear Region Filter
              </button>
            )}
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 gap-12">
            {/* Graph 1: The Master (Regional Volume) */}
            <div>
              <h4 className="text-sm font-medium text-gray-700 mb-6 flex items-center">
                1. Master: Volume by Sub-Region
              </h4>
              <div className="space-y-5">
                <InteractiveHorizontalBar label="DACH" value="15,240" percentage={85} active={activeRegionFilter} onClick={setActiveRegionFilter} color="bg-blue-600" />
                <InteractiveHorizontalBar label="UKI" value="12,100" percentage={70} active={activeRegionFilter} onClick={setActiveRegionFilter} color="bg-blue-600" />
                <InteractiveHorizontalBar label="France" value="9,450" percentage={55} active={activeRegionFilter} onClick={setActiveRegionFilter} color="bg-blue-600" />
                <InteractiveHorizontalBar label="Nordics" value="8,200" percentage={45} active={activeRegionFilter} onClick={setActiveRegionFilter} color="bg-blue-600" />
                <InteractiveHorizontalBar label="Benelux" value="3,942" percentage={25} active={activeRegionFilter} onClick={setActiveRegionFilter} color="bg-blue-600" />
              </div>
            </div>

            {/* Graph 2: The Detail (Persona Breakdown) */}
            <div className="bg-gray-50 rounded-lg p-6 border border-gray-100 flex flex-col">
              <h4 className="text-sm font-medium text-gray-700 mb-6 flex items-center justify-between">
                <span>2. Detail: Persona Breakdown</span>
                <span className="text-xs px-2 py-1 bg-white border border-gray-200 rounded text-gray-500">
                  {activeRegionFilter ? `Filtered: ${activeRegionFilter}` : 'All Regions'}
                </span>
              </h4>
              <div className="flex-1 flex items-end justify-around border-b border-gray-200 pb-2">
                {/* Dynamic Heights based on selection mock logic */}
                <DetailVerticalBar label="C-Suite" height={activeRegionFilter === 'DACH' ? 'h-3/4' : activeRegionFilter === 'UKI' ? 'h-1/4' : 'h-1/2'} color="bg-blue-800" value={activeRegionFilter === 'DACH' ? '45%' : activeRegionFilter === 'UKI' ? '12%' : '28%'} />
                <DetailVerticalBar label="IT DM" height={activeRegionFilter === 'DACH' ? 'h-1/2' : activeRegionFilter === 'UKI' ? 'h-4/5' : 'h-2/3'} color="bg-blue-500" value={activeRegionFilter === 'DACH' ? '30%' : activeRegionFilter === 'UKI' ? '65%' : '48%'} />
                <DetailVerticalBar label="Practitioner" height={activeRegionFilter === 'DACH' ? 'h-1/4' : activeRegionFilter === 'UKI' ? 'h-1/3' : 'h-2/5'} color="bg-blue-300" value={activeRegionFilter === 'DACH' ? '25%' : activeRegionFilter === 'UKI' ? '23%' : '24%'} />
              </div>
            </div>
          </div>
        </div>

        {/* SECTION 3: Pipeline Seniority Alignment */}
        <div className="bg-white p-6 rounded-lg border border-gray-200">
           <div className="mb-6 flex justify-between items-end">
            <div>
              <h3 className="text-base font-medium text-gray-800">Pipeline Seniority Alignment</h3>
              <p className="text-sm text-gray-500 mt-1">Select an Opportunity Practice Area to see the seniority of attached contacts.</p>
            </div>
            {activePracticeFilter && (
              <button onClick={() => setActivePracticeFilter(null)} className="text-sm text-blue-600 hover:text-blue-800 font-medium">
                Clear Practice Filter
              </button>
            )}
          </div>
          
          <div className="grid grid-cols-1 md:grid-cols-2 gap-12">
            {/* Graph 3: The Master (Pipeline Practice Areas) */}
            <div className="flex flex-col">
               <h4 className="text-sm font-medium text-gray-700 mb-6">
                1. Master: Pipeline Value by Area
              </h4>
              <div className="flex-1 flex items-end justify-around border-b border-gray-200 pb-2 mt-4">
                 <InteractiveVerticalColumn label="AI" value="$12.4M" height="h-full" active={activePracticeFilter} onClick={setActivePracticeFilter} color="bg-green-600" />
                 <InteractiveVerticalColumn label="Data Analytics" value="$8.2M" height="h-3/4" active={activePracticeFilter} onClick={setActivePracticeFilter} color="bg-green-600" />
                 <InteractiveVerticalColumn label="Security" value="$5.1M" height="h-1/2" active={activePracticeFilter} onClick={setActivePracticeFilter} color="bg-green-600" />
                 <InteractiveVerticalColumn label="Infrastructure" value="$3.8M" height="h-1/3" active={activePracticeFilter} onClick={setActivePracticeFilter} color="bg-green-600" />
              </div>
            </div>

            {/* Graph 4: The Detail (Seniority Rollup Heatmap/Bars) */}
            <div className="bg-gray-50 rounded-lg p-6 border border-gray-100 flex flex-col justify-center">
              <h4 className="text-sm font-medium text-gray-700 mb-6 flex items-center justify-between">
                <span>2. Detail: Contact Seniority Rollup</span>
                <span className="text-xs px-2 py-1 bg-white border border-gray-200 rounded text-gray-500">
                  {activePracticeFilter ? `Filtered: ${activePracticeFilter}` : 'All Practice Areas'}
                </span>
              </h4>
              <div className="space-y-6">
                 {/* Dynamic mock logic for detailed horizontal bars */}
                 <HorizontalBar label="Executive" percentage={activePracticeFilter === 'AI' ? 65 : activePracticeFilter === 'Security' ? 40 : 25} color="bg-yellow-500" />
                 <HorizontalBar label="Mid-Level (Director/Manager)" percentage={activePracticeFilter === 'Data Analytics' ? 70 : activePracticeFilter === 'Infrastructure' ? 50 : 45} color="bg-yellow-500" />
                 <HorizontalBar label="Technical Practitioner" percentage={activePracticeFilter === 'AI' ? 15 : activePracticeFilter === 'Infrastructure' ? 85 : 30} color="bg-yellow-500" />
              </div>
            </div>
          </div>
        </div>

        {/* SECTION 4: Trends */}
        <div className="bg-white p-6 rounded-lg border border-gray-200">
          <div className="flex justify-between items-center mb-6">
            <h3 className="text-base font-medium text-gray-800 flex items-center">
              <TrendingUp className="w-5 h-5 mr-2 text-blue-600" />
              Performance & Growth Trends
            </h3>
            
            {/* Granularity Parameter */}
            <div className="flex items-center bg-gray-100 p-0.5 rounded-md border border-gray-200">
              {['Week', 'Month', 'Quarter', 'Year'].map(t => (
                <button 
                  key={t}
                  onClick={() => setTrendGranularity(t)}
                  className={`px-3 py-1 text-sm rounded transition-all ${trendGranularity === t ? 'bg-white shadow-sm font-medium text-gray-800 border border-gray-200' : 'text-gray-500 hover:text-gray-800 border border-transparent'}`}
                >
                  {t}
                </button>
              ))}
            </div>
          </div>
          
          <div className="flex flex-col md:flex-row gap-8">
            <div className="w-full md:w-1/4 flex flex-col space-y-4">
              <div className="bg-gray-50 rounded-md p-4 border border-gray-100">
                <p className="text-sm text-gray-500 mb-1">Marketable Growth (New)</p>
                <p className="text-2xl font-normal text-gray-900">+1,245</p>
                <p className="text-xs text-green-600 mt-1 font-medium">vs previous {trendGranularity.toLowerCase()}</p>
              </div>
              <div className="bg-gray-50 rounded-md p-4 border border-gray-100">
                <p className="text-sm text-gray-500 mb-1">Net Marketable Growth</p>
                <p className="text-2xl font-normal text-gray-900">+890</p>
                <p className="text-xs text-gray-500 mt-1">New opt-ins minus churn</p>
              </div>
            </div>
            
            {/* Mock Line Graph */}
            <div className="w-full md:w-3/4 flex flex-col">
              <div className="flex justify-end space-x-6 mb-3 text-xs font-medium">
                <div className="flex items-center text-gray-600">
                  <div className="w-4 h-0.5 bg-blue-600 mr-2 rounded-full"></div> 
                  Marketable Contacts
                </div>
                <div className="flex items-center text-gray-600">
                  <div className="w-4 h-0.5 bg-gray-400 mr-2 rounded-full"></div> 
                  Total Contacts
                </div>
              </div>
              
              <div className="flex-1 min-h-[12rem] bg-white border border-gray-100 rounded-md relative flex flex-col shadow-sm">
                 {/* Grid Lines */}
                 <div className="absolute inset-0 flex flex-col justify-between pt-4 pb-8 px-4 z-0">
                    <div className="border-t border-gray-100 w-full h-0"></div>
                    <div className="border-t border-gray-100 w-full h-0"></div>
                    <div className="border-t border-gray-100 w-full h-0"></div>
                    <div className="border-t border-gray-200 w-full h-0"></div>
                 </div>

                 {/* SVG Lines */}
                 <svg className="absolute inset-0 w-full h-full pt-4 pb-8 px-4 z-10" preserveAspectRatio="none" viewBox="0 0 100 100">
                    {/* Total Contacts Line */}
                    <polyline points="0,75 20,65 40,60 60,40 80,25 100,10" fill="none" stroke="#9ca3af" strokeWidth="2" vectorEffect="non-scaling-stroke" strokeLinecap="round" strokeLinejoin="round" />
                    {/* Marketable Line */}
                    <polyline points="0,90 20,85 40,70 60,55 80,35 100,15" fill="none" stroke="#2563eb" strokeWidth="2.5" vectorEffect="non-scaling-stroke" strokeLinecap="round" strokeLinejoin="round" />
                 </svg>

                 {/* X-axis labels */}
                 <div className="absolute bottom-2 left-0 w-full flex justify-between px-4 text-xs text-gray-400 font-medium z-20">
                    <span>Jan</span>
                    <span>Feb</span>
                    <span>Mar</span>
                    <span>Apr</span>
                    <span>May</span>
                    <span>Jun</span>
                 </div>
              </div>
            </div>
          </div>
        </div>

        {/* SECTION 5: Actionable Drill-Through Table */}
        <div className="bg-white rounded-lg border border-gray-200 flex flex-col">
          <div className="p-6 border-b border-gray-200 flex justify-between items-center">
             <div>
              <h3 className="text-base font-medium text-gray-800">Actionable Roster</h3>
              <p className="text-sm text-gray-500 mt-1">Operational view updated by above charts</p>
             </div>
             
             {/* Active Filter Indicators */}
             {(activeRegionFilter || activePracticeFilter) && (
               <div className="flex items-center space-x-3">
                 <span className="text-sm text-gray-500">Filtered by:</span>
                 {activeRegionFilter && <span className="bg-blue-50 text-blue-700 border border-blue-200 text-xs px-2.5 py-1 rounded-md font-medium">{activeRegionFilter}</span>}
                 {activePracticeFilter && <span className="bg-blue-50 text-blue-700 border border-blue-200 text-xs px-2.5 py-1 rounded-md font-medium">{activePracticeFilter}</span>}
                 <button onClick={clearFilters} className="text-sm text-blue-600 hover:text-blue-800 ml-2 font-medium">Clear</button>
               </div>
             )}
          </div>
          
          <div className="overflow-x-auto">
            <table className="w-full text-left border-collapse text-sm">
              <thead>
                <tr className="bg-gray-50 border-b border-gray-200 text-gray-600">
                  <th className="px-6 py-3 font-medium">SFDC Person ID</th>
                  <th className="px-6 py-3 font-medium">Name</th>
                  <th className="px-6 py-3 font-medium">Account Name</th>
                  <th className="px-6 py-3 font-medium">Job Title</th>
                  <th className="px-6 py-3 font-medium">Region</th>
                  <th className="px-6 py-3 font-medium">Practice Area</th>
                  <th className="px-6 py-3 font-medium">Status</th>
                </tr>
              </thead>
              <tbody>
                {filteredData.length > 0 ? filteredData.map((row, i) => (
                  <tr key={i} className="border-b border-gray-100 hover:bg-gray-50 transition-colors">
                    <td className="px-6 py-4 font-mono text-xs text-gray-500">{row.id}</td>
                    <td className="px-6 py-4 text-gray-900">{row.name}</td>
                    <td className="px-6 py-4 text-blue-600 hover:underline cursor-pointer">{row.account}</td>
                    <td className="px-6 py-4 text-gray-600">{row.title}</td>
                    <td className="px-6 py-4 text-gray-600">{row.region}</td>
                    <td className="px-6 py-4 text-gray-600">{row.practice}</td>
                    <td className="px-6 py-4">
                      <span className={`flex items-center text-xs font-medium ${
                        row.status === 'Opted In' ? 'text-green-700' : 
                        row.status === 'Pending' ? 'text-yellow-700' : 
                        'text-red-700'
                      }`}>
                        <div className={`w-2 h-2 rounded-full mr-2 ${
                          row.status === 'Opted In' ? 'bg-green-500' : 
                          row.status === 'Pending' ? 'bg-yellow-500' : 
                          'bg-red-500'
                        }`}></div>
                        {row.status}
                      </span>
                    </td>
                  </tr>
                )) : (
                  <tr>
                    <td colSpan="7" className="p-8 text-center text-gray-500">
                      No contacts found matching the selected filters.
                    </td>
                  </tr>
                )}
              </tbody>
            </table>
          </div>
          <div className="p-4 bg-white border-t border-gray-200 flex justify-between items-center text-sm text-gray-500">
            <span>Showing {filteredData.length} records</span>
            <div className="flex space-x-2">
              <button className="px-4 py-1.5 border border-gray-300 rounded-md hover:bg-gray-50 disabled:opacity-50 text-gray-700 font-medium" disabled>Previous</button>
              <button className="px-4 py-1.5 border border-gray-300 rounded-md hover:bg-gray-50 text-gray-700 font-medium">Next</button>
            </div>
          </div>
        </div>

      </div>
    </div>
  );
}

// --- HELPER COMPONENTS ---

function FilterChip({ label, value }) {
  return (
    <button className="flex items-center px-3 py-1.5 bg-white border border-gray-300 rounded-full text-sm text-gray-700 hover:bg-gray-50 transition-colors shadow-sm shrink-0">
      <span className="font-medium text-gray-500 mr-1.5">{label}:</span>
      <span>{value}</span>
      <ChevronDown className="w-3.5 h-3.5 ml-1.5 text-gray-400" />
    </button>
  );
}

function FilterDropdown({ label }) {
  return (
    <button className="flex items-center text-sm font-medium text-gray-600 hover:text-gray-900 bg-white px-3 py-1.5 rounded border border-gray-300 transition-colors shadow-sm">
      {label}
      <ChevronDown className="w-4 h-4 ml-2 text-gray-400" />
    </button>
  );
}

function KpiCard({ title, value, icon, trend, trendPositive }) {
  return (
    <div className="bg-gray-50 p-6 rounded-lg border border-gray-100 flex flex-col justify-between">
      <div className="flex justify-between items-start mb-4">
        <h3 className="text-sm font-medium text-gray-600 leading-tight">{title}</h3>
        <div className="text-gray-400">{icon}</div>
      </div>
      <div className="flex items-end justify-between">
        <span className="text-3xl font-normal text-gray-900">{value}</span>
        {trend && (
          <span className={`text-sm font-medium ${trendPositive !== false ? 'text-green-600' : 'text-red-600'}`}>
            {trend}
          </span>
        )}
      </div>
    </div>
  );
}

function LegendItem({ color, label, value }) {
  return (
    <div className="flex items-center justify-between min-w-[140px]">
      <div className="flex items-center">
        <div className={`w-3 h-3 rounded-sm ${color} mr-3`}></div>
        <span className="text-gray-600">{label}</span>
      </div>
      {value && <span className="font-medium text-gray-900 ml-4">{value}</span>}
    </div>
  );
}

function HorizontalBar({ label, percentage, color }) {
  return (
    <div>
      <div className="flex justify-between text-sm mb-1.5">
        <span className="font-medium text-gray-700">{label}</span>
        <span className="text-gray-500">{percentage}%</span>
      </div>
      <div className="w-full bg-gray-200 rounded-full h-2">
        <div className={`${color} h-2 rounded-full transition-all duration-500`} style={{ width: `${percentage}%` }}></div>
      </div>
    </div>
  );
}

function InteractiveHorizontalBar({ label, value, percentage, active, onClick, color }) {
  const isActive = active === label;
  const isFaded = active !== null && !isActive;
  
  return (
    <div 
      className={`cursor-pointer group transition-opacity ${isFaded ? 'opacity-40' : 'opacity-100'}`} 
      onClick={() => onClick(isActive ? null : label)}
    >
      <div className="flex justify-between text-sm mb-1.5">
        <span className={`font-medium transition-colors ${isActive ? 'text-blue-700' : 'text-gray-700 group-hover:text-blue-600'}`}>
          {label}
        </span>
        <span className="text-gray-500">{value}</span>
      </div>
      <div className="w-full bg-gray-100 rounded-full h-2">
        <div className={`${color} h-2 rounded-full transition-all`} style={{ width: `${percentage}%` }}></div>
      </div>
    </div>
  );
}

function InteractiveVerticalColumn({ label, value, height, active, onClick, color }) {
  const isActive = active === label;
  const isFaded = active !== null && !isActive;

  return (
    <div 
      className={`flex flex-col items-center justify-end h-48 w-16 cursor-pointer group transition-opacity ${isFaded ? 'opacity-40' : 'opacity-100'}`}
      onClick={() => onClick(isActive ? null : label)}
    >
      <span className="text-xs text-gray-500 mb-2">{value}</span>
      <div className={`w-full ${height} ${isActive ? color : 'bg-gray-400 group-hover:bg-gray-500'} rounded-t-[2px] transition-colors`}></div>
      <span className={`text-center text-sm font-medium mt-3 truncate w-full px-1 ${isActive ? 'text-green-700' : 'text-gray-700'}`}>
        {label}
      </span>
    </div>
  )
}

function DetailVerticalBar({ label, height, color, value }) {
  return (
    <div className="flex flex-col items-center justify-end h-48 w-1/4">
      <span className="text-xs font-medium text-gray-600 mb-2">{value}</span>
      <div className={`w-full ${height} ${color} rounded-t-[2px] transition-all duration-500`}></div>
      <span className="text-center text-sm font-medium text-gray-700 mt-3">{label}</span>
    </div>
  )
}
